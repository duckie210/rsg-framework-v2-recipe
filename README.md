# RSG Framework v2 - pinned 2.x txAdmin recipe

A txAdmin recipe for the RSG RedM framework as it was **before the move to v3**
(October 2026). It is based on the official
[Rexshack-RedM/txAdminRecipe](https://github.com/Rexshack-RedM/txAdminRecipe) at commit
`1a1d959` (2026-10-02), the last recipe before v3 resources were added.

The official recipe downloads every resource from `main`, which now gives you v3 code.
This recipe pins **every resource to a specific commit**, so it always installs the 2.x versions.

## Use in txAdmin

In the txAdmin setup, choose **Remote URL Template** and paste:

```
https://raw.githubusercontent.com/duckie210/rsg-framework-v2-recipe/main/rsgcore.yaml
```

## Changes from the official 2026-10-02 recipe

- Every `download_github` task pinned to a commit (`ref: <sha>`); oxmysql switched from the CommunityOx fork to the official
  [overextended/oxmysql](https://github.com/overextended/oxmysql) release v2.14.1 (needs an FXServer build with Node 22 support).
- v3 resources swapped back for the 2.x resources they replaced (now archived under `RexShack/`):
  - `rsg-character` -> `rsg-multicharacter`, `rsg-appearance`, `rsg-spawn`
  - `rsg-stores` -> `rsg-shops`
  - `rsg-chat` -> `chat-redm`
- v3 resources removed: `rsg-backpacks`, `rsg-cooking`.
- Added 2.x resources: `rsg-discord`, `rsg-robbery`.
- Manual pins: `rsg-wardrobe` 2.0.2, `rsg-prison` 2.0.3, `rsg-bathing` 1.1.6 (versions before they switched to `rsg-character`).
- Moved repos repointed: `weathersync` and `rsg-horses` now live under `RexShack/`.
- `rsgcore.sql`: removed v3-only tables `player_backpack`, `rsg_shops_npcs`, `rsg_shops_items`,
  `rsg_shops_blips`, `rsg_cooking_campfires`.
- `server.cfg`: `ensure rsg-character` -> `ensure rsg-multicharacter` + `ensure rsg-spawn`;
  `ensure rsg-chat` -> `ensure chat-redm`.

See [PINS.md](PINS.md) for every resource, its pinned commit and version.

## After install

- **rsg-discord** needs `config.js` (copy `config.example.js`) with your Discord bot token and guild ID,
  otherwise it errors on start.
- Set `steam_webApiKey` in `server.cfg` if you use Steam.

## Credits

All resources are by [Rexshack-RedM](https://github.com/Rexshack-RedM) / RexShack and their
contributors, plus the third-party resources listed in the recipe. Join the RSG Discord:
https://discord.gg/eW3ADkf4Af

# Pre-v3 txAdmin recipe (1a1d959) - resource pins

| resource | basis | pinned commit | manifest version | notes |
|---|---|---|---|---|
| txAdminRecipe | recipe files | 1a1d959 | - | recipe itself (server.cfg, rsgcore.sql, logo) |
| cfx-server-data | external/moved | c6afa39 | - | citizenfx/cfx-server-data: unchanged since 2026-09-23 |
| ox_lib | no 2.x; state before cutoff | 5391d32 (2026-03-28) | 3.32.3 | unchanged since |
| progressbar | no 2.x; state before cutoff | 3a6ae3b (2023-02-26) | - | unchanged since |
| PolyZone | 2.x (still 2.x at HEAD) | 9dab54d (2025-02-19) | 2.6.2 |  |
| pma-voice | external/moved | 6c9d96e | - | AvarianKnight/pma-voice: unchanged since 2026-06-17 |
| weathersync | external/moved | d4e8867 | - | RexShack/weathersync: MOVED to RexShack/weathersync; old URL 404s; unchanged since 2024-05-05 |
| xsound | external/moved | 7b345f8 | - | Xogy/xsound: unchanged since 2025-11-10 |
| interact-sound | no 2.x; state before cutoff | 1e08586 (2025-12-24) | 1.0.2 | unchanged since |
| menu_base | no 2.x; state before cutoff | 1660eda (2023-07-04) | - | unchanged since |
| rNotify | no 2.x; state before cutoff | c01531d (2023-09-04) | - | unchanged since |
| ox_target | 2.x snapshot | a032493 (2026-06-03) | 2.0.3 |  |
| ox_doorlock | 2.x (still 2.x at HEAD) | 60e1e24 (2025-12-24) | 2.0.2 |  |
| redm-female-fix | external/moved | 1cff974 | - | Popisek/redm-female-fix: unchanged since 2026-07-17 |
| rsg-core | 2.x snapshot | 18a6987 (2026-10-03) | 2.4.1 |  |
| rsg-inventory | 2.x snapshot | 6e1019d (2026-10-03) | 2.9.2 |  |
| rsg-multicharacter | external/moved | d8a9555 | - | RexShack/rsg-multicharacter: MOVED to RexShack/rsg-multicharacter, archived; final 2.x = v2.3.5 (2026-05-31) |
| rsg-appearance | external/moved | b661402 | - | RexShack/rsg-appearance: MOVED to RexShack/rsg-appearance, archived; final 2.x = v2.5.6 (2026-09-23) |
| rsg-spawn | external/moved | 6615dfc | - | RexShack/rsg-spawn: MOVED to RexShack/rsg-spawn, archived; final 2.x = v2.0.6 (2026-09-22) |
| rsg-wardrobe | manual pin | 1be95a1 (2026-06-16) | 2.0.2 | pinned before f99ef4b 'support rsg-character' (2026-09-26); uses rsg-appearance |
| rsg-medic | 2.x snapshot | 387d5c3 (2026-09-19) | 2.2.1 |  |
| rsg-lawman | 2.x (still 2.x at HEAD) | 8c4e46d (2026-06-13) | 2.0.6 |  |
| rsg-prison | manual pin | 70e9db0 (2025-12-24) | 2.0.3 | pinned before 705ce41 'fix apply skin bug' (2026-09-28) which calls rsg-character |
| rsg-doorlock | no 2.x; state before cutoff | fcdd9a3 (2026-04-03) | 1.0.3 | unchanged since |
| rsg-banking | 2.x snapshot | 65f2a7b (2026-05-30) | 2.1.1 |  |
| rsg-weapons | 2.x (still 2.x at HEAD) | f461b87 (2026-09-20) | 2.1.10 |  |
| rsg-ammo | 2.x (still 2.x at HEAD) | c8e0eff (2025-12-24) | 2.1.6 |  |
| rsg-shops | external/moved | b79c57c | - | RexShack/rsg-shops: MOVED to RexShack/rsg-shops, archived; final 2.x = v2.1.3 (HEAD 2026-09-13) |
| rsg-radialmenu | 2.x (still 2.x at HEAD) | 5c6f907 (2026-09-26) | 2.0.0 |  |
| rsg-essentials | 2.x snapshot | 34777cc (2026-10-10) | 2.3.14 |  |
| rsg-telegram | 2.x snapshot | c01d5fc (2026-09-07) | 2.1.1 |  |
| rsg-horses | external/moved | 9f4885a | - | RexShack/rsg-horses: MOVED to RexShack/rsg-horses, archived 2026-10-01 at v2.3.3 |
| rsg-hud | 2.x snapshot | 7bcf5af (2026-10-01) | 2.2.0 |  |
| rsg-menubase | no 2.x; state before cutoff | 671a4dc (2026-07-30) | 1.1.6 | 1 later commit(s) not included |
| rsg-playerinfo | 2.x (still 2.x at HEAD) | 4f55175 (2025-12-24) | 2.0.1 |  |
| rsg-bossmenu | 2.x snapshot | 60f773f (2026-06-13) | 2.0.4 |  |
| rsg-gangmenu | 2.x snapshot | e6446e5 (2026-04-03) | 2.0.3 |  |
| rsg-npcs | 2.x (still 2.x at HEAD) | 9d820c5 (2025-12-24) | 2.0.5 |  |
| rsg-canteen | 2.x snapshot | 36b6317 (2025-12-24) | 2.0.3 |  |
| rsg-barbers | 2.x (still 2.x at HEAD) | 4a2a779 (2026-04-03) | 2.0.7 |  |
| rsg-bathing | manual pin | f11101b (2026-08-29) | 1.1.6 | pinned before a612199 (2026-09-26) which only changed the fxmanifest dependency to rsg-character; same code, depends on rsg-appearance |
| rsg-lockpick | no 2.x; state before cutoff | 6fc0893 (2025-10-12) | 1.0.0 | unchanged since |
| rsg-adminmenu | 2.x snapshot | 7641734 (2026-09-09) | 2.1.2 |  |
| rsg-animations | 2.x snapshot | 4f32eb5 (2026-07-13) | 2.0.2 |  |
| rsg-multijob | 2.x (still 2.x at HEAD) | d564029 (2026-09-27) | 2.0.8 |  |
| rsg-consume | 2.x snapshot | 9999c45 (2026-10-10) | 2.0.3 |  |
| rsg-fishing | 2.x snapshot | 2134bd9 (2026-09-27) | 2.0.6 |  |
| rsg-weaponcomp | 2.x (still 2.x at HEAD) | 9d4541b (2026-09-27) | 2.8.3 |  |
| rsg-loading | 2.x snapshot | a25891e (2026-09-27) | 2.0.0 |  |
| rsg-mdt | 2.x (still 2.x at HEAD) | a63d3e8 (2026-06-06) | 2.0.10 |  |
| rsg-hunting | 2.x (still 2.x at HEAD) | afb660c (2026-10-03) | 2.0.2 | 1 commit(s) since 2026-10-03 without leaving 2.x - review |
| rsg-herbalist | 2.x snapshot | ca464d9 (2026-10-03) | 2.0.5 |  |
| chat-redm | external/moved | f05a27d | - | RexShack/chat-redm: MOVED to RexShack/chat-redm, archived; v1.0.0, unchanged since 2025-08-27 |
| rsg-hotair | 2.x (still 2.x at HEAD) | 2f0e5a2 (2026-09-27) | 2.0.1 |  |
| rsg-samples | 2.x (still 2.x at HEAD) | aa97f17 (2026-10-02) | 2.1.0 |  |
| rsg-track | 2.x (still 2.x at HEAD) | 4dc2142 (2026-09-27) | 2.0.1 |  |
| rsg-goldclaim | 2.x snapshot | a4bde71 (2026-10-04) | 2.0.3 |  |
| rsg-wagons | 2.x (still 2.x at HEAD) | 3eeca3d (2026-09-27) | 2.0.3 |  |
| rsg-railroad | 2.x (still 2.x at HEAD) | c612dc2 (2026-10-04) | 2.0.3 | 3 commit(s) since 2026-10-03 without leaving 2.x - review |
| rsg-huntingpets | 2.x (still 2.x at HEAD) | 118190c (2026-10-05) | 2.0.2 | 2 commit(s) since 2026-10-03 without leaving 2.x - review |
| rsg-trapdoors | 2.x (still 2.x at HEAD) | afe49db (2026-09-27) | 2.0.0 |  |
| rsg-fishmonger | 2.x (still 2.x at HEAD) | 6f55d79 (2026-09-30) | 2.0.0 |  |
| rsg-looting | 2.x (still 2.x at HEAD) | be25d38 (2026-09-28) | 2.0.1 |  |
| rsg-lumberjack | 2.x snapshot | 4ef0f04 (2026-10-01) | 2.0.0 |  |
| rsg-discord | 2.x (still 2.x at HEAD) | 4e5d211 (2025-11-24) | 2.0.0 |  |
| rsg-robbery | 2.x (still 2.x at HEAD) | 5b85d17 (2026-09-27) | 2.0.0 |  |
| Nt_Blackjack | external/moved | 5017113 | - | Nubetastic/Nt_Blackjack: state before cutoff; repo has a newer commit on 2026-10-05 |
| Nt_Holdem | external/moved | f2578b1 | - | Nubetastic/Nt_Holdem: state before cutoff; repo has a newer commit on 2026-10-05 |
| redm-ipls | no 2.x; state before cutoff | e48f3c8 (2025-12-24) | 1.0.2 | unchanged since |
| redm-ymaps | no 2.x; state before cutoff | 278805b (2023-03-03) | - | unchanged since |
| oxmysql | external release | v2.12.3 | - | latest release (repo archived 2026-02-20) |

Excluded from pinned recipe: **rsg-backpacks** - v3-only resource (repo created 2026-09-30, added to recipe 2026-10-01).

Excluded from pinned recipe: **rsg-cooking** - v3 resource (confirmed by user; 2026-10-10 recipes use v3-only rsg-core items).

Replaced in pinned recipe: **rsg-character** -> rsg-multicharacter, rsg-appearance, rsg-spawn - v3 resource (repo created 2026-09-24); replaced rsg-multicharacter, rsg-appearance and rsg-spawn in recipe commit 39c6e0e (2026-09-26).

Replaced in pinned recipe: **rsg-stores** -> rsg-shops - v3-era resource (repo created 2026-09-11); replaced rsg-shops in recipe commit 3878854 (2026-09-15).

Replaced in pinned recipe: **rsg-chat** -> chat-redm - v3-era resource (repo created 2026-09-19); replaced chat-redm in recipe commit 5f7d29e (2026-09-19).

## Review of "commits since 2026-10-03 without leaving 2.x"
Checked against rsg-core 2.x (18a6987) `shared/items.lua`. All safe to keep at HEAD:
- rsg-railroad (3 commits, 2026-10-04): switched items to `resource_coal` / `resource_iron_bar` / `resource_gold_bar` etc. These names already exist in 2.x rsg-core; the old `iron_bar` / `steel_bar` did not, so this is a fix.
- rsg-hunting (1 commit): snake-skin typo fixes (`resource_skin_snake_*`), matching 2.x rsg-core.
- rsg-huntingpets (2 commits): small item/locale/config tweaks.
- rsg-wardrobe (1 commit): Romanian locale only.
- rsg-menubase: pinned to 671a4dc (pre-cutoff); later commit eee3320 (2026-10-11) adds UI JS/CSS features.

## SQL: pre-v3 (1a1d959) vs current HEAD
- 64 tables pre-v3, 89 at HEAD.
- Added for v3: horse_race_tracks, rsg_auction_*, rsg_bank_* (accounts, home, loans, lockbox_items, lockboxes, meta, transactions), rsg_farming_plants, rsg_farming_wellpumps, rsg_imaps, rsg_loyalty, rsg_mining, rsg_mining_workers, rsg_shops_presets, rsg_smelting_state, rsg_stables_breeding, rsg_stables_horses, rsg_telegram_contacts, rsg_telegrams, rsg_trader, rsg_trader_npcs, rsg_trapdoors_schema, rsg_weather_state.
- Present pre-v3 but gone at HEAD: address_book, player_horses, telegrams (replaced by rsg_telegram* / rsg_stables_horses).
- The 2026-10-02 admin_* / player_playtime tables are pre-v3: rsg-adminmenu 2.1.2 (7641734) already uses them.

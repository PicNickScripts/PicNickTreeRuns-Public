# PicNickTreeRuns

![PicNickTreeRuns](https://raw.githubusercontent.com/PicNickScripts/PicNickTreeRuns-Public/main/assets/picnicktreeruns-200.png)

PicNickTreeRuns is a DreamBot Farming script by PicNick for standard tree and fruit tree runs.

## Current Public Status

| Item | Status |
| --- | --- |
| Public Version | v0.20 |
| DreamBot SDN | Pending DreamBot approval |
| Java Target | Java 8 bytecode |
| Source Format | Single-module DreamBot SDN layout |
| Ironman Support | Planned supply/shop flow where requirements and owned supplies allow |
| QuickStart | Not enabled |

## What It Covers

| Area | Coded Knowledge |
| --- | --- |
| Standard Trees | Lumbridge, Varrock, Falador, Taverley, Gnome Stronghold, Farming Guild |
| Fruit Trees | Gnome Stronghold, Tree Gnome Village, Catherby, Brimhaven, Lletya, Farming Guild |
| Transport | Teleports, spirit trees, fairy rings, Farming cape, Grand/Royal seed pod, Construction cape, house portals, charter/boat fallbacks |
| Ironman Sourcing | Farming shops, Farming Guild shops, farmers, tool leprechauns, Garden Supplier awareness, sapling preparation notes |
| Patch Actions | Check-health first, rake when needed, compost priority, plant, protection handling, tree/fruit tree clear modes |
| Runtime Safety | Members-world validation/hop attempt, bank-first supply checks, bounded fallback attempts, sanitized report flow |

## Start Here

- [Setup](Setup) - how the script starts, validates membership/world state, and saves settings.
- [Patch Routing](Patch-Routing) - every coded tree and fruit tree patch route family.
- [Ironman](Ironman) - coded shop/supply knowledge and sapling-prep workflow.
- [Normal Accounts](Normal-Accounts) - GE restock intent, coins, tools, saplings, compost, and transport supplies.
- [Humanization](Humanization) - public-safe overview of default-on interaction behavior.
- [Coded Knowledge](Coded-Knowledge) - sapling levels, transport activation coverage, and reportable validation tables.
- [History](History) - historical public update notes matching the Discord release-post style.
- [Support](Support) - Discord invite and sanitized Report Bug overlay flow.

## Recent v0.20 Notes

- Public release artifacts only; proprietary source is not distributed.
- Support/report flow and OSRS-chatbox overlay polish.
- Fixed live Farming level sync so level 1 accounts no longer inherit stale saved levels.
- Reset saved tree and fruit sapling selections when they exceed the live account level.
- Cleaned local saved startup data that previously carried Farming 75/Magic/Palm selections.
- Transport priority is documented separately for Normal and Ironman accounts with numbered fallbacks.

## Important Availability Note

DreamBot approval is required before SDN availability. The public GitHub repository contains release artifacts and documentation only; the proprietary source is not distributed there.

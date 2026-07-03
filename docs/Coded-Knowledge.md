# Coded Knowledge

Use this page as a public validation sheet. If a user sees a mismatch in-game, report it through the overlay Report Bug flow and Discord support channel.

## Standard Tree Saplings

| Priority | Sapling | Farming Level |
| --- | --- | --- |
| 1 | Oak sapling | 15 |
| 2 | Willow sapling | 30 |
| 3 | Maple sapling | 45 |
| 4 | Yew sapling | 60 |
| 5 | Magic sapling | 75 |

## Fruit Tree Saplings

| Priority | Sapling | Farming Level |
| --- | --- | --- |
| 1 | Apple sapling | 27 |
| 2 | Banana sapling | 33 |
| 3 | Orange sapling | 39 |
| 4 | Curry sapling | 42 |
| 5 | Pineapple sapling | 51 |
| 6 | Papaya sapling | 57 |
| 7 | Palm sapling | 68 |
| 8 | Dragonfruit sapling | 81 |

## Transport Activation Coverage

The route planner can rank many routes. v0.14 adds live activation attempts for these supported transport families when the item, spellbook, runes, or equipped item are available:

| Family | Supported Examples | Notes |
| --- | --- | --- |
| Standard spellbook | Lumbridge, Varrock, Falador, Camelot, Ardougne, Watchtower, Teleport to House | Uses DreamBot spell availability checks before casting. |
| Lunar spellbook | Catherby Teleport | Requires active Lunar spellbook and castable runes. |
| Arceuus spellbook | Battlefront Teleport | Requires active Arceuus spellbook and castable runes. |
| Tablets / scrolls | Lumbridge, Varrock, Falador, Camelot, Ardougne, Taverley, Catherby, Battlefront, Iorwerth camp | Uses inventory item action attempts first where present. |
| Capes | Construct. cape, Farming cape, Achievement diary cape | Can use inventory or equipped cape actions where the game exposes them. |
| Jewelry / charged items | Skills necklace, Ring of wealth, Games necklace, Combat bracelet, Slayer ring, Amulet of glory, Explorer's ring, Necklace of passage | Uses inventory or equipment slot actions with route-specific options first. |
| Seeds / crystals | Grand seed pod, Royal seed pod, Teleport crystal family | Uses item actions when available, then falls back safely. |

## Report A Knowledge Mismatch

Include:

1. The sapling, patch, teleport, or shop that looked wrong.
2. The Farming level and account type.
3. The selected Simple/Advanced settings.
4. The sanitized Report Bug text from the overlay.

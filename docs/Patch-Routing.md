# Patch Routing

## Normal Account Transport Priority

Normal accounts use the highest available route first, then fall down the numbered list when a route is missing, out of charges, locked, or fails validation.

| Priority | Patch / Destination | Teleport Spot Used |
| --- | --- | --- |
| 1 | Taverley tree patch | Construction cape to Taverley house portal |
| 2 | Falador tree patch | Ring of wealth to Falador Park |
| 3 | Farming Guild fruit tree patch | Spirit tree planted in Farming Guild |
| 4 | Catherby fruit tree patch | Catherby teleport destination |
| 5 | Brimhaven fruit tree patch | Construction cape to Brimhaven house portal |
| 6 | Gnome Stronghold fruit tree patch | Balloon transport or spirit tree to Tree Gnome Stronghold |
| 7 | Gnome Stronghold tree patch | Slayer ring to Stronghold Slayer Cave, then Tree Gnome Stronghold route |
| 8 | Farming Guild tree patch | Skills necklace to Farming Guild |
| 9 | Varrock tree patch | Varrock teleport destination or Grand Exchange ring/teleport route |
| 10 | Lumbridge tree patch | Lumbridge teleport destination |
| 11 | Tree Gnome Village fruit tree patch | Spirit tree to Tree Gnome Village |
| 12 | Lletya fruit tree patch | Teleport crystal to Lletya |

## Ironman Transport Priority

Ironman accounts use the same patch destinations, but Grand Exchange restock routes are skipped and any buyable/restocked teleport is only useful when already owned or sourced through valid account progression.

| Priority | Patch / Destination | Ironman-Friendly Teleport Spot Used |
| --- | --- | --- |
| 1 | Taverley tree patch | Construction cape to Taverley house portal, then balloon transport, then owned Taverley house/tablet route |
| 2 | Farming Guild fruit tree patch | Spirit tree planted in Farming Guild, Farming cape teleport, then skills necklace if owned |
| 3 | Falador tree patch | Ring of wealth to Falador Park if owned, then Falador teleport, then Mining Guild skills necklace if owned |
| 4 | Brimhaven fruit tree patch | Construction cape to Brimhaven house portal, then Brimhaven house portal, then spirit tree planted in Brimhaven |
| 5 | Gnome Stronghold fruit tree patch | Balloon transport, spirit tree to Stronghold, Achievement diary cape to Elder gnome child, then Grand/Royal seed pod |
| 6 | Gnome Stronghold tree patch | Spirit tree or balloon route, then Grand/Royal seed pod, then Gnome glider |
| 7 | Catherby fruit tree patch | Catherby teleport if unlocked/owned, then Gnome glider to White Wolf Mountain, then charter ship |
| 8 | Varrock tree patch | Varrock teleport, then spirit tree to Grand Exchange only as a travel hub, not GE restock |
| 9 | Lumbridge tree patch | Lumbridge teleport, Achievement diary cape to Hatius Cosaintus, then Draynor bank walk |
| 10 | Tree Gnome Village fruit tree patch | Spirit tree to Tree Gnome Village, then fairy ring CIQ, then Construction cape Yanille portal walk |
| 11 | Lletya fruit tree patch | Teleport crystal, then Construction cape Prifddinas portal walk, then Iorwerth camp teleport walk |
| 12 | Farming Guild tree patch | Skills necklace if owned, Farming cape teleport, spirit tree planted in Farming Guild, then fairy ring CIR |

## Standard Tree Patches

| Patch | Requirement Note | Coded Transport Knowledge |
| --- | --- | --- |
| Lumbridge tree patch | None | Lumbridge teleport; Achievement diary cape to Hatius Cosaintus; Draynor bank walk fallback |
| Varrock tree patch | None | Varrock teleport; Spirit tree to Grand Exchange; Ring of wealth Grand Exchange; Skills necklace Cooking Guild; Grand Exchange teleport fallback |
| Falador tree patch | None | Ring of wealth Falador Park; Falador teleport; Skills necklace Mining Guild; Explorer's ring fallback |
| Taverley tree patch | None | Construction cape Taverley portal; Balloon transport to Taverley; Taverley house portal; Taverley teleport; Games necklace Burthorpe; Burthorpe games room minigame teleport; Goblin village sphere; Combat bracelet Warriors' Guild; Catherby teleport grapple route; Falador teleport walk fallback |
| Gnome Stronghold tree patch | Tree Gnome Village access strongly preferred | Slayer ring Stronghold Slayer Cave; Spirit tree to Stronghold; Balloon transport; Grand/Royal seed pod; Gnome glider; Necklace of passage Outpost |
| Farming Guild tree patch | 65 Farming for tree patch guild entry | Skills necklace Farming Guild; Farming cape teleport; Spirit tree planted in Farming Guild; Lovakengj Minecart; Fairy ring CIR; Battlefront teleport walk fallback |

## Fruit Tree Patches

| Patch | Requirement Note | Coded Transport Knowledge |
| --- | --- | --- |
| Gnome Stronghold fruit tree patch | Tree Gnome Village access strongly preferred | Balloon transport; Spirit tree to Stronghold; Achievement diary cape to Elder gnome child; Grand/Royal seed pod; Slayer ring Stronghold Slayer Cave; Gnome glider; Necklace of passage Outpost |
| Tree Gnome Village fruit tree patch | Tree Gnome Village maze access | Spirit tree to Village; Fairy ring CIQ; Construction cape Yanille portal walk; Yanille teleport walk fallback |
| Catherby fruit tree patch | None | Catherby teleport; Gnome glider White Wolf Mountain; Charter ship to Catherby; Camelot teleport walk fallback |
| Brimhaven fruit tree patch | Karamja access | Construction cape Brimhaven portal; Brimhaven house portal; Spirit tree planted in Brimhaven; Ardougne teleport boat route; Charter ship to Brimhaven; Karamja gloves route; Fairy ring BJR plus magic whistle; Amulet of glory Karamja walk |
| Lletya fruit tree patch | Mourning's End Part I access | Teleport crystal; Construction cape Prifddinas portal walk; Iorwerth camp teleport walk fallback |
| Farming Guild fruit tree patch | 85 Farming for west wing fruit tree | Spirit tree planted in Farming Guild; Farming cape teleport; Skills necklace Farming Guild; Lovakengj Minecart; Fairy ring CIR; Battlefront teleport walk fallback |

## Fairy Ring Rule

Fairy ring routes are coded with this requirement: Fairy Tale II started and fairy ring access; equip Dramen staff or Lunar staff unless Lumbridge & Draynor elite diary removes the staff requirement.

## Construction Cape Rule

When the account has 99 Construction and owns a Construct. cape or Construct. cape(t), the gear manager prioritizes wearing it to save inventory space. Routes can then use its unlimited Teleport / Tele to POH options for Taverley, Brimhaven, Yanille fallback, and Prifddinas/Lletya fallback paths.

## Route Safety

- The script starts with bank validation.
- It checks members access before Farming route actions.
- A patch is no longer counted complete unless at least one live patch action confirms success.
- Failed live action chains are logged with [PATCH-FAIL].

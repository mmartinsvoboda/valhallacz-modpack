# ValhallaCZ Modpack

Shared Valheim Thunderstore modpack package and player setup docs for the private `ValhallaCZ` server.

## Server

- Name: `ValhallaCZ`
- Direct IP: shared privately
- Password: shared privately
- Crossplay: off
- Visibility: private / not listed

## For Players

Valheim dedicated servers do not send BepInEx mods to clients. Each player must install the same modpack locally and launch through r2modman.

See [docs/PLAYER_SETUP.md](docs/PLAYER_SETUP.md).

### Current Install Path

The Thunderstore package exists, but r2modman can lag behind Thunderstore's public package page while its searchable package index refreshes. If `ValhallaCZ_Modpack` is not visible in r2modman search, import the prepared r2modman profile file instead:

- r2modman profile import file: [dist/ValhallaCZ.r2z](dist/ValhallaCZ.r2z)
- Raw download URL: https://raw.githubusercontent.com/mmartinsvoboda/valhallacz-modpack/main/dist/ValhallaCZ.r2z

Use r2modman `Import/Update` -> `Import new profile` -> `From file`, then select `ValhallaCZ.r2z`. This installs the same indexed underlying mods and copies the shared config files.

## Package

- Upload-ready Thunderstore zip: [dist/ValhallaCZ_Modpack-1.0.0.zip](dist/ValhallaCZ_Modpack-1.0.0.zip)
- r2modman profile import file: [dist/ValhallaCZ.r2z](dist/ValhallaCZ.r2z)
- Thunderstore package source: [package/](package/)
- Publishing notes: [docs/PUBLISHING.md](docs/PUBLISHING.md)
- Mod overview: [docs/MODS_OVERVIEW.md](docs/MODS_OVERVIEW.md)

## Included Mods

- `denikson-BepInExPack_Valheim-5.4.2333`
- `Azumatt-AzuCraftyBoxes-1.8.14`
- `Azumatt-AzuAutoStore-3.0.14`
- `Goldenrevolver-Quick_Stack_Store_Sort_Trash_Restock-1.4.13`
- `TastyChickenLegs-AutomaticFuel-1.4.8`
- `Azumatt-AzuAreaRepair-1.1.6`
- `Azumatt-SleepSkip-1.3.0`
- `Advize-PlantEasily-2.1.1`
- `Azumatt-AAA_Crafting-2.1.6`
- `Azumatt-AzuHoverStats-1.1.9`
- `Azumatt-ItemCompare-1.0.9`
- `Azumatt-AzuClock-1.0.5`

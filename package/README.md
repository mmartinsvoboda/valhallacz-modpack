# ValhallaCZ Modpack

Shared Valheim QoL modpack for the private ValhallaCZ server.

## Server

- Name: `ValhallaCZ`
- Direct IP: shared privately
- Password: shared privately
- Crossplay: off
- Server visibility: private / not listed

## Required Client Workflow

Valheim dedicated servers do not send BepInEx mods to clients. Every player must install this modpack locally and start Valheim through the mod manager.

1. Install r2modman from Thunderstore or GitHub.
2. Select `Valheim`.
3. Create or select a profile named `ValhallaCZ`.
4. Install this modpack.
5. Launch with `Start modded`.
6. Join using the connection details shared privately.

Launching Valheim directly from Steam starts the vanilla game and will fail against this modded server.

## Included Mods

- BepInExPack Valheim `5.4.2333`
- AzuCraftyBoxes `1.8.14`
- AzuAutoStore `3.0.14`
- Quick Stack - Store - Sort - Trash - Restock `1.4.13`
- AutomaticFuel `1.4.8`
- AzuAreaRepair `1.1.6`
- SleepSkip `1.3.0`
- PlantEasily `2.1.1`
- AAA Crafting `2.1.6`
- AzuHoverStats `1.1.9`
- ItemCompare `1.0.9`
- AzuClock `1.0.5`

The server controls synced gameplay configuration where the individual mods support ServerSync. `AzuAreaRepair` and `SleepSkip` are installed on both the server and clients. The farming and UI helper mods are client-side quality-of-life additions.

### What They Do

- BepInExPack Valheim: the loader required for Valheim mods.
- AzuCraftyBoxes: craft and build using materials from nearby chests.
- AzuAutoStore: store dropped/inventory items into nearby containers and search storage.
- Quick Stack - Store - Sort - Trash - Restock: inventory buttons and shortcuts for stacking, sorting, restocking, trashing, and favoriting.
- AutomaticFuel: automatically fuels torches, fires, kilns, smelters, windmills, spinning wheels, and similar stations from nearby storage/drops.
- AzuAreaRepair: repairs damaged build pieces in an area instead of one piece at a time.
- SleepSkip: lets the server skip night when the configured share of players accepts the sleep vote.
- PlantEasily: grid planting, easier crop placement, bulk harvest, and farming workflow helpers.
- AAA Crafting: crafting UI improvements such as craft amount controls, search, and recipe tracking.
- AzuHoverStats: useful hover details for plants, fires, fermenters, chests, and build pieces.
- ItemCompare: compares hovered/craftable equipment against currently equipped items.
- AzuClock: adds a small in-game clock.

## Updating

When the server mod list changes, update this modpack version and have all players update the modpack before joining.

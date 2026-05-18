# ValhallaCZ Player Setup

Valheim does not download BepInEx mods from the server. Each player must install the same modpack locally.

## Recommended Setup While r2modman Search Catches Up

1. Install r2modman from one of the official sources:
   - Thunderstore: https://thunderstore.io/c/valheim/p/ebkr/r2modman/
   - GitHub: https://github.com/ebkr/r2modmanPlus
2. Open r2modman and select `Valheim`.
3. On the profile screen, click `Import/Update`.
4. Choose `Import new profile`.
5. Choose `From file`.
6. Select the prepared profile import file:
   - [../dist/ValhallaCZ.r2z](../dist/ValhallaCZ.r2z)
   - Raw download: https://raw.githubusercontent.com/mmartinsvoboda/valhallacz-modpack/main/dist/ValhallaCZ.r2z
7. Let r2modman download and install all listed mods.
8. Select the imported `ValhallaCZ` profile.
9. Start the game with `Start modded`.

This `.r2z` file is an r2modman profile export. It lists the underlying Thunderstore mods directly and includes the shared config files. Use it when r2modman search cannot find `ValhallaCZ_Modpack` yet.

## Thunderstore Package Setup

Once r2modman search/indexing shows the package:

1. Open r2modman and select `Valheim`.
2. Create or select a profile named `ValhallaCZ`.
3. Search for `ValhallaCZ_Modpack`.
4. Install the package by `ValhallaCZ`.
5. Accept/download dependencies.
6. Start the game with `Start modded`.

## Join

- Server: `ValhallaCZ`
- Direct IP: shared privately
- Password: shared privately

Do not launch from Steam directly for this server. Steam launches vanilla Valheim, which will show an incompatible version/mod mismatch.

## Updating later

When mods change, update the r2modman profile from the latest `.r2z` file or update `ValhallaCZ_Modpack` in r2modman once the package is visible in search.

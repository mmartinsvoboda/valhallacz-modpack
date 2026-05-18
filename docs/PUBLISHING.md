# Publishing ValhallaCZ_Modpack

The package zip is built under `dist/`.

## Player Import Fallback

`dist/ValhallaCZ.r2z` is a r2modman profile import file for players. Keep this file available while Thunderstore/r2modman indexing lags behind the public package page.

Players can use it through r2modman:

1. Select `Valheim`.
2. Click `Import/Update` on the profile screen.
3. Choose `Import new profile`.
4. Choose `From file`.
5. Select `ValhallaCZ.r2z`.

This bypasses the `ValhallaCZ_Modpack` package lookup and installs the underlying indexed dependencies directly.

## Upload

1. Open Thunderstore in the Valheim community.
2. Create or select a team for the server, for example `ValhallaCZ`.
3. Upload the generated `ValhallaCZ_Modpack-1.0.0.zip`.
4. Select the `Modpacks` category.
5. Publish.

Thunderstore package uploads require a logged-in Thunderstore account/team, so this step cannot be completed from the server without your account/session or an API token.

## Updating

For every future server mod change:

1. Update `package/manifest.json`.
2. Update `package/CHANGELOG.md`.
3. Rebuild the Thunderstore zip.
4. Rebuild or export a matching `dist/ValhallaCZ.r2z` profile file.
5. If publishing a new Thunderstore release, increment `version_number` because uploaded Thunderstore versions are immutable.
6. Upload the new version to the same Thunderstore package/team if publishing through Thunderstore.
7. Tell players to update the modpack or import the latest `.r2z` before joining.

# Publishing ValhallaCZ_Modpack

The package zip is built under `dist/`.

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
2. Increment `version_number`.
3. Update `package/CHANGELOG.md`.
4. Rebuild the zip.
5. Upload the new version to the same Thunderstore package/team.
6. Tell players to update the modpack in r2modman before joining.

# Call2Prayer.PROPlus 2026.8.13.2

Channel: stable

Tag: v2026.8.13.2

Package: C2P.PROPlus.Update.v2026.8.13.2.zip

## Included changes

- Corrects update-package generation to exclude runtime paths protected by the production updater, without changing normal publish or installer content.
- Hardened playback-endpoint enumeration against invalid Windows audio endpoint metadata.
- Derives the licensed network health probe from `Bootstrap.ApiBaseUrl` as `/health`.
- Removes the retired hard-coded Azure license endpoint from connectivity probes.

## Validation

- Release build completed successfully.
- Network connectivity focused tests passed (9/9).
- Full updater test suite passed (61/61).
- Exact ZIP validated successfully with the frozen Gate B updater package-validation contract.
- Protected runtime paths and updater self-update files are excluded from the update package.

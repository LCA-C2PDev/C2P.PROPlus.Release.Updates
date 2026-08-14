# Call2Prayer.PROPlus 2026.8.13.1

Channel: stable

Tag: v2026.8.13.1

Package: C2P.PROPlus.Update.v2026.8.13.1.zip

## Included changes

- Hardened playback-endpoint enumeration against invalid Windows audio endpoint metadata.
- Derives the licensed network health probe from `Bootstrap.ApiBaseUrl` as `/health`.
- Removes the retired hard-coded Azure license endpoint from connectivity probes.

## Validation

- Release build completed successfully.
- Network connectivity focused tests passed (9/9).
- Full updater test suite passed (61/61).

# C2P.PROPlus.Release.Updates

This repository hosts release metadata for `Call2Prayer.PROPlus` application updates.

## Current Status

- preview channel is active
- stable channel is not published yet
- current preview version: `2026.5.9.2`
- current preview tag: `preview-v2026.5.9.2`
- current preview package asset: `C2P.PROPlus.Update.v2026.5.9.2.zip`

## Structure

```text
releases/
  latest-stable.json
  latest-preview.json
  v2026.5.9.2/
    C2P.PROPlus.Update.v2026.5.9.2.json
    C2P.PROPlus.ReleaseNotes.v2026.5.9.2.md
```

## Notes

- `latest-preview.json` points to the current preview update
- `latest-stable.json` remains unset until a stable update is promoted
- version folders contain release-specific metadata and release notes
- no customer files are stored in this repository
- no license files are stored in this repository

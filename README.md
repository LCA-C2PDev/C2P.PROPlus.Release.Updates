# C2P.PROPlus.Release.Updates

This repository hosts release metadata for `Call2Prayer.PROPlus` application updates.

## Current Status

- stable channel is active
- current stable version: `2026.9.6.1`
- current stable tag: `v2026.9.6.1`
- current stable package asset: `C2P.PROPlus.Update.v2026.9.6.1.zip`
- preview channel remains available independently

## Structure

```text
releases/
  latest-stable.json
  latest-preview.json
  v2026.9.6.1/
    C2P.PROPlus.Update.v2026.9.6.1.json
    C2P.PROPlus.Update.v2026.9.6.1.release.json
    C2P.PROPlus.Update.v2026.9.6.1.sha256.txt
    C2P.PROPlus.Update.v2026.9.6.1.validation-report.json
    C2P.PROPlus.ReleaseNotes.v2026.9.6.1.md
```

## Notes

- `latest-preview.json` points to the current preview update
- `latest-stable.json` points to the current production update
- version folders contain release-specific metadata and release notes
- binary update ZIPs are attached to matching GitHub Releases rather than committed to Git
- no customer files are stored in this repository
- no license files are stored in this repository

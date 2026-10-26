# C2P.PROPlus.Release.Updates

This repository hosts release metadata for `Call2Prayer.PROPlus` application updates.

## Current Status

- stable channel is active
- Major Stable 2026.10.20.1 corrects MP3 playlist progression, adds Scheduler PAUSE/PLAY/STOP and confirmed CANCEL CURRENT EVENT, and promotes the Dhuhr/Asr prayer-offset refinements
- current stable version: `2026.10.20.1` (Major Stable)
- current stable tag: `v2026.10.20.1`
- current stable package asset: `C2P.PROPlus.Update.v2026.10.20.1.zip`
- current preview version: `2026.10.26.1`
- current preview tag: `preview-v2026.10.26.1`
- current preview package asset: `C2P.PROPlus.Update.v2026.10.26.1.zip`
- the separately distributed full installer remains at v2026.9.6.1
- Preview `2026.10.26.1` adds multi-channel Yoctopuce relay assignment for Athan Player and Scheduler. It builds on Preview `2026.10.25.1` per-module audio output routing.
- Preview and Stable channels remain separate

## Structure

```text
releases/
  latest-stable.json
  latest-preview.json
  v2026.10.26.1/
    C2P.PROPlus.Update.v2026.10.26.1.json
    C2P.PROPlus.Update.v2026.10.26.1.release.json
    C2P.PROPlus.Update.v2026.10.26.1.sha256.txt
    C2P.PROPlus.Update.v2026.10.26.1.validation-report.json
    C2P.PROPlus.ReleaseNotes.v2026.10.26.1.md
  v2026.10.20.1/
    C2P.PROPlus.Update.v2026.10.20.1.json
    C2P.PROPlus.Update.v2026.10.20.1.release.json
    C2P.PROPlus.Update.v2026.10.20.1.sha256.txt
    C2P.PROPlus.Update.v2026.10.20.1.validation-report.json
    C2P.PROPlus.ReleaseNotes.v2026.10.20.1.md
  v2026.9.6.1/
    C2P.PROPlus.Update.v2026.9.6.1.json
    C2P.PROPlus.Update.v2026.9.6.1.release.json
    C2P.PROPlus.Update.v2026.9.6.1.sha256.txt
    C2P.PROPlus.Update.v2026.9.6.1.validation-report.json
    C2P.PROPlus.ReleaseNotes.v2026.9.6.1.md
  v2026.10.4.1/
    C2P.PROPlus.Update.v2026.10.4.1.json
    C2P.PROPlus.Update.v2026.10.4.1.release.json
    C2P.PROPlus.Update.v2026.10.4.1.sha256.txt
    C2P.PROPlus.ReleaseNotes.v2026.10.4.1.md
  v2026.10.6.1/
    C2P.PROPlus.Update.v2026.10.6.1.json
    C2P.PROPlus.Update.v2026.10.6.1.release.json
    C2P.PROPlus.Update.v2026.10.6.1.sha256.txt
    C2P.PROPlus.ReleaseNotes.v2026.10.6.1.md
    C2P.PROPlus.Update.v2026.10.6.1.stable.json
    C2P.PROPlus.Update.v2026.10.6.1.stable.release.json
    C2P.PROPlus.Update.v2026.10.6.1.stable.sha256.txt
    C2P.PROPlus.StableReleaseNotes.v2026.10.6.1.md
  v2026.10.7.1/
    C2P.PROPlus.Update.v2026.10.7.1.json
    C2P.PROPlus.Update.v2026.10.7.1.release.json
    C2P.PROPlus.Update.v2026.10.7.1.sha256.txt
    C2P.PROPlus.Update.v2026.10.7.1.validation-report.json
    C2P.PROPlus.ReleaseNotes.v2026.10.7.1.md
  v2026.10.15.1/
    C2P.PROPlus.Update.v2026.10.15.1.json
    C2P.PROPlus.Update.v2026.10.15.1.release.json
    C2P.PROPlus.Update.v2026.10.15.1.sha256.txt
    C2P.PROPlus.Update.v2026.10.15.1.validation-report.json
    C2P.PROPlus.ReleaseNotes.v2026.10.15.1.md
```

## Notes

- `latest-preview.json` points to the current preview update
- `latest-stable.json` points to the current production update
- version folders contain release-specific metadata and release notes
- binary update ZIPs are attached to matching GitHub Releases rather than committed to Git
- no customer files are stored in this repository
- no license files are stored in this repository

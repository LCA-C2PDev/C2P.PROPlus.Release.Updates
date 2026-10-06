# Changelog

## 2026.10.6.1-stable

- promoted the tested `2026.10.6.1` Preview source to the Stable application update channel
- rebuilt the package with Stable informational version `v2026.10.6 - Build 26100601` and published it under tag `v2026.10.6.1`
- retained the separate Preview package, tag, and feed pointer at `preview-v2026.10.6.1`
- Stable package SHA-256: `3472C2E2E8300994264B192BF4FD87AA4D2C103753A38F82DCFA5F5460405EB1`
- the separately distributed full installer remains at v2026.9.6.1

## 2026.10.6.1-preview

- published `Call2Prayer PROPlus` version `2026.10.6.1` to the preview update channel
- fixed scheduled Athan recovery for qualifying audio-output failures with one retry inside the existing 10-second start grace
- added explicit playback outcome/failure diagnostics and audio endpoint state details
- retained Scheduler and Fingerprint V2 preview functionality
- retained stable version `2026.9.6.1` and the original stable installer


## 2026.10.4.1-preview

- published `Call2Prayer PROPlus` version `2026.10.4.1` to the preview update channel
- added the installed-features and interface details About card plus Contact & Support links
- added Fingerprint V2 license compatibility across the preview workflow
- retained stable version `2026.9.6.1` and the original stable installer

## 2026.10.1.1-preview

- published `Call2Prayer PROPlus` version `2026.10.1.1` to the preview update channel
- opening the Scheduler workspace again reuses and activates its existing calendar window
- retained stable version `2026.9.6.1` and the original stable installer

## 2026.9.30.1-preview

- published `Call2Prayer PROPlus` version `2026.9.30.1` to the preview update channel
- added licensed calendar scheduling with smoother handover between AudioManager and scheduled playback
- coordinated optional USB relay timing with scheduled audio
- added a user-facing About tab with version, preview highlights, and update information
- retained stable version `2026.9.6.1` and the original stable installer

## 2026.9.6.1-stable

- published `Call2Prayer.PROPlus` version `2026.9.6.1` to the stable channel
- changed operator-facing and internal module naming from `MusicManager` to `AudioManager`
- retained backward-compatible license activation for legacy `MusicManager` entitlements
- added migration handling for existing MusicManager configuration, layout, and media locations
- added package compatibility and isolated updater validation records
- set the stable package asset to `C2P.PROPlus.Update.v2026.9.6.1.zip`

## 2026.5.9.2-preview-feed

- prepared preview metadata for `Call2Prayer.PROPlus`
- set preview tag to `preview-v2026.5.9.2`
- set package asset name to `C2P.PROPlus.Update.v2026.5.9.2.zip`
- kept stable metadata unpublished
- confirmed no customer files or license files are part of the release feed

## 2026.5.9.2-preview

- initialized preview-first update metadata repository
- added preview channel pointers
- added release metadata and release notes for `v2026.5.9.2`
- stable channel intentionally left unpublished

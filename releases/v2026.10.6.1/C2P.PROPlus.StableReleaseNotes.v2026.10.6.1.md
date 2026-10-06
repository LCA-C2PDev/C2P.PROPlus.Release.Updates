# Call2Prayer PROPlus 2026.10.6.1 Stable

Channel: stable

Tag: v2026.10.6.1

Package: C2P.PROPlus.Update.v2026.10.6.1.zip

This Stable application update promotes Preview 2026.10.6.1. It includes licensed Scheduler playback and its FullCalendar/WebView2 workspace, Fingerprint V2 license validation with legacy compatibility, the revised Settings → About view, and the focused scheduled Athan output-failure recovery fix.

Athan playback distinguishes natural completion, intentional stop, and playback failure. Qualifying scheduled Athan output failures permit at most one recovery attempt, starting within the original 10-second trigger grace. Preview and Dua playback, manual/intentional stops, normal completion, and replacement playback do not retry. The Scheduler entitlement and prayer-first audio/relay authority remain in force.

The Stable ZIP was rebuilt with informational version `v2026.10.6 - Build 26100601` and passed compatibility updater validation. Its SHA-256 is `3472C2E2E8300994264B192BF4FD87AA4D2C103753A38F82DCFA5F5460405EB1`. The 128 updater tests and isolated apply/bad-hash/unsafe-path scenarios passed during Preview fix validation. Test actual audio endpoint failure/recovery, licensed relay timing, WebView2, and activation on the target PC.

This update supports installed version 2026.9.6.1 or later. Preview 2026.10.6.1 and Stable 2026.10.6.1 have the same numeric application version, so the in-app updater will not offer the Stable build as newer to an installation already running that Preview version. The separately distributed full installer remains the prior v2026.9.6.1 package.

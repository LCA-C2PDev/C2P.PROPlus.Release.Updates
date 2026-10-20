# Call2Prayer PROPlus 2026.10.20.1 — Major Stable

This Stable milestone combines the existing Stable Scheduler/prayer-continuation line with the Preview prayer-offset refinements and corrected Scheduler MP3 playlist progression and operator controls.

- MP3 playlists advance from decoded end of stream, including files whose decoded position remains below advertised Length. RepeatCount=1 plays the complete playlist once; RepeatCount=2 plays it twice.
- Scheduler right-click PAUSE, PLAY, and STOP provide transport control. STOP retains the occurrence, current track and repeat progress for restart; the event's absolute maximum duration still applies.
- CANCEL CURRENT EVENT ends the current occurrence and its remaining tracks/repeats after confirmation. A captured occurrence identity prevents stale confirmation from cancelling a later event. Future events and valid queued occurrences remain eligible.
- Unexpected playback failures terminate through the normal relay/AudioManager ownership-release path. Explicit stop/pause and stale output callbacks cannot advance tracks.
- Dhuhr and Asr offsets accept -25 to +100 minutes; all other prayer profiles, including Friday, remain at -10 to +10 minutes. Every prayer-offset fader has a longer gold zero marker.

The Scheduler entitlement, prayer authority, format-3 event compatibility, Fingerprint V2 support, and bounded scheduled Athan recovery remain in effect. Preview remains at 2026.10.15.1. The independent updater remains 2026.4.14.2; full-installer distribution is separate.

Verification: 175 Release tests passed, 0 failed, and 1 opt-in audible test was skipped. The self-contained win-x64 package passed previous-Stable-updater validation and isolated apply (0), bad-hash rejection (22), and unsafe-path rejection (23). The operator separately confirmed audible progression of both short MP3 tracks. Automated decoder/fake-output and simulated relay checks do not establish physical relay timing or audible behavior of the new controls.

Package: `C2P.PROPlus.Update.v2026.10.20.1.zip` (76,447,516 bytes).
SHA-256: `687B19F6461EA53E508A19ABBC17474D91E0C820F45E5E231522ECC4B7EA8FCC`.

Informational version: `v2026.10.20 - Major Stable Build 26102001`.

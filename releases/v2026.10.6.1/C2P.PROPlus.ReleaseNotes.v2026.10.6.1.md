# Call2Prayer PROPlus 2026.10.6.1 Preview

Channel: preview

Tag: preview-v2026.10.6.1

Package: C2P.PROPlus.Update.v2026.10.6.1.zip

This Preview advances the Scheduler and Fingerprint V2 line with a focused fix for scheduled Athan playback failures caused by the audio output path. Stable production version 2026.9.6.1 and its installer remain unchanged.

Athan playback now distinguishes natural completion, intentional stop, and playback failure while preserving the existing playback-stopped event contract. Output failures include a failure category and HRESULT when available. Failed output initialization or startup cleans up partial playback resources, and endpoint diagnostics record endpoint state and error details.

A retry is limited to one recovery attempt for a failed scheduled Athan, and only when that attempt can start by the existing ScheduledAt + 10-second deadline. That deadline limits when a new attempt starts, not the duration of audio that has started. Preview and Dua playback, manual or intentional stops, normal completion, and replacement playback are not retried. Prayer scheduling and other business behavior remain unchanged.

The update supports installed version 2026.9.6.1 or later. The Release app and updater built successfully. The package passed updater compatibility validation and isolated apply, bad-hash, and unsafe-path scenarios (exit codes 0, 22, and 23). The 128-test updater suite passed during the fix validation. Test actual endpoint invalidation and recovery on the target audio hardware before wider operator use. The stable installer and stable update channel remain unchanged.

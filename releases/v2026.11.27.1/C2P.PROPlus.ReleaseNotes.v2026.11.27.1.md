# Call2Prayer PROPlus 2026.11.27.1 Preview

Channel: preview

Tag: preview-v2026.11.27.1

Package: C2P.PROPlus.Update.v2026.11.27.1.zip

This Preview replaces automatic short-term Serilog retention with permanent daily JSON audit logs in `DATA/LOGS/YYYY-MM-MMM/`. Logs link consecutive dates using `CARRY_FORWARD` and `BROUGHT_FORWARD`; restart recovery creates continuity-only files for missed calendar days. Month rollover creates the new folder and next daily file automatically.

Interrupted writes are checkpointed and recovered without rewriting a valid audit tail. If a damaged log cannot safely be completed, its bytes are preserved and logging continues in a recovery segment with the break reported. Diagnostics searches the nested monthly log folders.

An empty or unverified log history begins with `AUDIT_FORMAT_STARTED`. `FIRST_APPLICATION_RUN` requires installer-provided identity proof and is not asserted by this Preview.

The Release suite passed 272 tests (1 skipped, 0 failed). The win-x64 update package passed compatibility validation with the previous Preview updater. Package size: 76,576,478 bytes. SHA-256: 4805A4D5F615B267BEF3CD4140A01CF527682A8CA50521F1062C63AEE7032B34.

Perform target-PC verification for normal daily creation, month rollover, shutdown/restart, missed-day continuity, and damaged-log recovery. Stable 2026.10.20.1 and the separate full installer remain unchanged.

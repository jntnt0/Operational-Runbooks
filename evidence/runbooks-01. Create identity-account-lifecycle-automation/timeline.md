# Timeline

Tag: A/B
Runbook: /runbooks/01. Create identity-account-lifecycle-automation.md

- T0:
- T1:
- T2:





Example timeline entry format:
```md
2026-02-22 19:41 ET  Fault injected: added LAB-sso-blocked to LAB-CA-Block
2026-02-22 19:43 ET  Observed: portal.office.com blocked; correlation ID xxxxx
2026-02-22 19:44 ET  Triage: sign-in logs show CA policy "Block sign-in" applied
2026-02-22 19:46 ET  Fix: removed user from LAB-CA-Block
2026-02-22 19:47 ET  Verified: sign-in succeeds; My Apps loads
2026-02-22 19:50 ET  Cleanup: re-added u
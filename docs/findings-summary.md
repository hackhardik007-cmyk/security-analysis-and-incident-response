# Findings Summary

## Summary

This coursework project combines security concepts and practical lab exercises across cloud data protection, data classification, encoded PowerShell review, Windows process monitoring, and incident-response scenarios. Work was performed in an isolated virtual environment using Kali Linux and Windows 10 VMs.

## Observations

- Encoding can conceal script content, but behavior must be reviewed to assess risk.
- Process, file, registry, and startup telemetry provide complementary clues during endpoint triage.
- Cloud data controls should be matched to data sensitivity and access requirements.
- Incident response should prioritize containment, evidence preservation, credential hygiene, and follow-up monitoring.

## Defensive Implications

- Reduce unnecessary exposure and review insecure defaults.
- Improve authentication, patching, endpoint visibility, and logging based on the relevant risk.
- Validate suspected issues before assigning severity or declaring exploitability.
- Preserve evidence and maintain a clear scope during any security assessment.

## Limitations

This was a course assignment in a controlled lab. Cloud and incident-response portions include scenario-based analysis; they are not a production cloud audit or live incident response engagement.

## Publication Notes

This summary intentionally avoids raw target details, credentials, payloads, and unredacted evidence. Do not add those materials to a public repository.

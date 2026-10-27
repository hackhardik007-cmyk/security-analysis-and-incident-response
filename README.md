# CEH Capstone: Security Analysis, Script Review, and System Monitoring

> Coursework project | CEH v12 curriculum | Intellipaat

## Overview

This coursework project combines security concepts and practical lab exercises across cloud data protection, data classification, encoded PowerShell review, Windows process monitoring, and incident-response scenarios. Work was performed in an isolated virtual environment using Kali Linux and Windows 10 VMs.

## Objectives

- Document the methodology and observations from the course lab.
- Explain security implications in clear, defensible terms.
- Connect observations to practical defensive recommendations.
- Keep public documentation sanitized and reproducible at a high level.

## Lab and Tools

- CyberChef
- Kali Linux command-line utilities
- Sysinternals Process Explorer
- Sysinternals Process Monitor
- Autoruns

## Methodology

1. Reviewed cloud security controls, including encryption, role-based access control, data classification, and monitoring.
2. Decoded a Base64/UTF-16LE PowerShell sample for static review; encoding alone is not proof of maliciousness.
3. Inspected the decoded script behavior and documented downloader-like indicators without publishing live payloads or operational indicators.
4. Used Process Explorer, Process Monitor, and Autoruns to observe process relationships, file/registry activity, and startup entries.
5. Documented phishing-response and incident-containment recommendations as scenario-based coursework.

## Key Findings

- Encoding can conceal script content, but behavior must be reviewed to assess risk.
- Process, file, registry, and startup telemetry provide complementary clues during endpoint triage.
- Cloud data controls should be matched to data sensitivity and access requirements.
- Incident response should prioritize containment, evidence preservation, credential hygiene, and follow-up monitoring.

## Defensive Recommendations

- Apply least privilege and remove or restrict services that are not required.
- Keep operating systems, applications, and security tools updated.
- Use strong unique passwords and multifactor authentication where available.
- Centralize and review relevant endpoint, authentication, and network logs.
- Validate scanner or tool output before treating it as a confirmed vulnerability.
- Preserve evidence and document scope during incident investigation.

## Scope and Limitations

This was a course assignment in a controlled lab. Cloud and incident-response portions include scenario-based analysis; they are not a production cloud audit or live incident response engagement.

## Ethics and Safety

All hands-on activity described here was coursework conducted in a lab context. Only assess systems for which you have explicit authorization. This repository contains documentation only; it does not distribute payloads, credentials, malware, or raw target scan data.

## Repository Structure

- `docs/methodology.md` — concise workflow and tool purpose.
- `docs/findings-summary.md` — summarized observations, implications, and limitations.
- `evidence/README.md` — guidance for adding sanitized screenshots, if permitted.
- `.gitignore` — excludes common temporary and sensitive files.

## Coursework Disclaimer

This project documents learning exercises from the CEH v12 curriculum. It is not evidence of a commercial security engagement or a certification exam pass.

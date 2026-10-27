# Methodology

## Project

CEH Capstone: Security Analysis, Script Review, and System Monitoring

## Environment and Scope

This coursework project combines security concepts and practical lab exercises across cloud data protection, data classification, encoded PowerShell review, Windows process monitoring, and incident-response scenarios. Work was performed in an isolated virtual environment using Kali Linux and Windows 10 VMs.

## Tools and Their Purpose

- CyberChef
- Kali Linux command-line utilities
- Sysinternals Process Explorer
- Sysinternals Process Monitor
- Autoruns

## Workflow

1. Reviewed cloud security controls, including encryption, role-based access control, data classification, and monitoring.
2. Decoded a Base64/UTF-16LE PowerShell sample for static review; encoding alone is not proof of maliciousness.
3. Inspected the decoded script behavior and documented downloader-like indicators without publishing live payloads or operational indicators.
4. Used Process Explorer, Process Monitor, and Autoruns to observe process relationships, file/registry activity, and startup entries.
5. Documented phishing-response and incident-containment recommendations as scenario-based coursework.

## Validation and Safety

- Treat tool output as an observation that may require manual validation.
- Avoid publishing secrets, account details, private IPs, full scan outputs, or unredacted screenshots.
- Keep any follow-up testing inside an explicitly authorized lab.
- Do not infer that a system is secure solely because a scan did not report a critical finding.

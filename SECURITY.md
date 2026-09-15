# Security Policy

We take the security of Puku CLI seriously. This document explains how to report a vulnerability and what to expect from us.

## Supported versions

We provide security updates for the latest released version of Puku CLI. Older versions may receive fixes on a best-effort basis, but we strongly recommend running the latest release.

| Version | Supported |
| ------- | --------- |
| Latest  | ✅ Yes    |
| Older   | ⚠️ Best-effort |

## Reporting a vulnerability

**Please do not file a public GitHub issue for security vulnerabilities.**

Instead, report privately through one of these channels:

1. **Email:** `security@puku.sh`
2. **GitHub private security advisory:** use the "Security" tab on this repository and choose "Report a vulnerability" to open a private advisory.

Either channel reaches our security team directly.

## What to include

To help us triage quickly, please include:

- **Affected version** of Puku CLI (run `puku --version`)
- **Operating system** and version
- **Reproduction steps** — minimal steps that reliably trigger the issue
- **Impact assessment** — what an attacker could achieve
- **Whether the issue is already public** — links, posts, or CVEs if applicable
- **Proof-of-concept code or commands** if available (kept confidential)

## Response timeline

- **Acknowledgment:** within 72 hours of your report
- **Triage decision:** within 7 days — we'll confirm whether we can reproduce and assess severity
- **Patch timeline:** varies by severity; critical issues are prioritized
- **Credit:** with your permission, we'll credit you in the fix release notes

## Disclosure policy

We follow **coordinated disclosure**:

- We ask reporters to keep vulnerability details confidential until we have released a fix.
- We'll work with you on a reasonable disclosure timeline and notify you before any public announcement.
- Once a fix is released, we'll publish a security advisory describing the issue, its impact, and credit to the reporter (unless you prefer to remain anonymous).

## Out of scope

The following are **not** considered security vulnerabilities and should be filed as regular bug reports instead:

- Crashes without security impact
- Performance or usability issues
- Feature requests
- General questions about Puku CLI behavior

For questions about whether something qualifies, email `security@puku.sh` first and we'll point you to the right channel.

## Thank you

Responsible disclosure helps keep Puku CLI users safe. We appreciate your effort and partnership.

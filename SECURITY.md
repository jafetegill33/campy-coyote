# Security Policy

Campy Coyote takes system security seriously, with a focus on stability,
transparency, and responsible disclosure.

This document defines how security issues should be reported and handled.

---

## Supported Versions

Security updates apply to:

- The current stable Campy Coyote release
- Actively developed pre-release branches, where applicable

End-of-life releases do not receive security updates.

---

## Reporting a Security Vulnerability

If you discover a potential security vulnerability:

**Do NOT open a public GitHub issue.**

Instead, report it privately to the project maintainers using the contact
method listed in the repository (e.g. security email or private GitHub contact).

Your report should include:
- A clear description of the issue
- Steps to reproduce, if applicable
- Affected components or versions
- Potential impact assessment

Incomplete reports may delay response.

---

## Disclosure Process

Campy Coyote follows responsible disclosure practices:

1. Report is received and acknowledged
2. Issue is investigated and validated
3. Fix is developed and tested
4. Patch is released
5. Public disclosure occurs after mitigation

Coordinated disclosure timelines will be respected when possible.

---

## Upstream Vulnerabilities

Campy Coyote is based on Ubuntu LTS.

- Many security issues originate upstream
- Ubuntu Security Notices (USNs) are inherited where applicable
- Campy-specific tooling and configuration are reviewed independently

Where upstream fixes exist, they are preferred over downstream patching.

---

## Security Philosophy

- Security must not compromise user control
- No security through obscurity
- Fixes must be auditable and documented
- Silent changes are avoided

Security is treated as part of system integrity, not an afterthought.

---

## Final Note

If you are unsure whether an issue is security-related, err on the side of
private disclosure.

Responsible reporting helps keep Campy Coyote reliable and trustworthy.

---

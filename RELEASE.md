# Campy Coyote Release Process

This document defines how Campy Coyote releases are planned, built, verified,
and published.

The goal of the release process is **predictability, auditability, and trust**.

---

## Release Types

Campy Coyote uses the following release categories:

### 1. Stable Releases
- Based on Ubuntu LTS
- Intended for daily use
- Fully supported according to the project lifecycle

Example:
Campy Coyote 24.04 LTS

---

### 2. Release Candidates (RC)
- Feature-complete
- Intended for testing
- May contain known issues
- Clearly marked as non-final

Example:
Campy Coyote 24.04 RC1

---

### 3. Development Snapshots
- Built from active development branches
- No stability guarantees
- Intended for contributors only

Snapshots are not advertised as releases.

---

## Versioning Scheme

Campy Coyote versions follow this format:


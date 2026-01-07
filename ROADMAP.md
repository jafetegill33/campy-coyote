# Campy Coyote Roadmap

This roadmap outlines the intended direction of the Campy Coyote project.

It is a planning document, not a promise.
Dates are approximate.
Scope may change based on feasibility and alignment with the manifesto.

---

## Phase 0 — Foundation (Current)

**Goal:** Establish philosophical, legal, and structural clarity.

Status:
- Manifesto ratified
- Governance documents in place
- Project identity defined

Deliverables:
- MANIFESTO.md
- README.md
- CONTRIBUTING.md
- CODE_OF_CONDUCT.md
- SECURITY.md

---

## Phase 1 — Minimal System Bring-Up

**Goal:** Produce a bootable, minimal Campy Coyote system.

Deliverables:
- Debian/Ubuntu-based rootfs via debootstrap
- Minimal package set
- Networking and basic user login
- Reproducible build scripts
- Clear build documentation

Outcome:
- Proof-of-life artifact
- Text or minimal graphical environment

---

## Phase 2 — Tooling and Identity

**Goal:** Establish Campy-specific tooling and identity.

Deliverables:
- `campyctl` (core CLI utility)
- System identification (`/etc/os-release`)
- Branding assets (minimal)
- Repository layout for Campy packages

Outcome:
- System clearly identifiable as Campy Coyote
- Minimal divergence from upstream

---

## Phase 3 — Installer and ISO

**Goal:** Enable clean installation on real hardware.

Deliverables:
- Bootable hybrid ISO (BIOS + UEFI)
- SquashFS-based live system
- Calamares installer integration
- Offline installation support (where feasible)

Outcome:
- Installable distribution
- First public release candidate

---

## Phase 4 — First Stable Release

**Goal:** Release Campy Coyote 24.04 LTS.

Deliverables:
- Signed ISO
- Checksums and verification instructions
- Release notes
- Upgrade policy documentation

Outcome:
- Stable baseline for users and contributors
- Long-term maintenance begins

---

## Phase 5 — Refinement (Post-Release)

**Goal:** Improve without expanding scope.

Potential work:
- Performance tuning
- Documentation expansion
- Optional desktop variants
- Improved update tooling
- Snapshot / rollback research

No scope expansion without manifesto alignment.

---

## Non-Goals

The following are explicitly out of scope unless re-ratified:

- Rolling release model
- Monetization or ads
- Telemetry
- Vendor lock-in
- Rapid feature expansion

---

## Roadmap Governance

- Roadmap changes must align with the manifesto
- Major direction changes require public discussion
- The maintainer(s) retain final decision authority

---

## Closing

Campy Coyote favors slow, deliberate progress over rapid expansion.

The goal is not growth.
The goal is correctness.

---

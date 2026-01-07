# Campy Coyote

Campy Coyote is a minimal, stable, and developer-oriented Linux distribution based on Ubuntu LTS.

It is designed for users who value control, clarity, and performance over abstraction, automation, and excess.

Campy Coyote provides a strong foundation and then gets out of the way.

---

## Philosophy

Campy Coyote is governed by a clear and explicit philosophy documented in the
[Campy Coyote Manifesto](./MANIFESTO.md).

The manifesto defines:
- What Campy Coyote is
- What it deliberately refuses to become
- The guarantees made to users
- The expectations placed on maintainers and contributors

All technical decisions are expected to align with this document.

---

## Key Characteristics

- **Ubuntu LTS base**
- **Minimal default installation**
- **No telemetry**
- **No forced package formats**
- **Predictable updates**
- **Low resource usage**
- **Transparent configuration**

Stability and user sovereignty take precedence over novelty.

---

## What Campy Coyote Is Not

Campy Coyote is not:
- A rolling release
- A vendor ecosystem
- A themed showcase distribution
- A monetized platform
- A beginner-only abstraction layer

It does not chase trends.
It does not optimize for marketing.
It does not trade control for convenience.

---

## Project Structure

```text
campy-coyote/
├── MANIFESTO.md        # Foundational philosophy and social contract
├── README.md           # Project overview and entry point
├── docs/               # Technical documentation
├── build/              # ISO and rootfs build tooling
├── branding/           # Visual identity assets
└── tooling/            # campyctl and related utilities

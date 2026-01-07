# Contributing to Campy Coyote

Thank you for your interest in contributing to Campy Coyote.

Campy Coyote is a minimal, stable, and user-sovereign Linux distribution based on
Ubuntu LTS. Contributions are welcome **only when they align with the project’s
foundational principles**.

Before contributing, you are strongly encouraged to read the
[Campy Coyote Manifesto](./MANIFESTO.md).

---

## Scope of Contributions

We welcome contributions in the following areas:

- Build scripts and reproducible tooling
- Distribution-specific utilities (e.g. `campyctl`)
- Documentation and technical writing
- Installer integration and configuration
- Branding assets (when explicitly requested)
- Bug fixes and performance improvements
- Infrastructure (CI, mirrors, signing)

Contributions that expand scope without clear justification will be rejected.

---

## Guiding Principles

All contributions must adhere to these rules:

1. **Stability over novelty**
2. **Clarity over abstraction**
3. **User control over automation**
4. **Transparency over convenience**
5. **Minimalism with justification**

If a change violates the manifesto, it will not be merged — regardless of
technical quality.

---

## What Will Not Be Accepted

The following are out of scope:

- Forced package formats or ecosystems
- Telemetry, analytics, or tracking
- Undocumented background services
- Feature creep without measurable benefit
- Cosmetic changes without functional value
- Marketing-driven additions

This list is not exhaustive.

---

## Contribution Workflow

### 1. Open an Issue First (Recommended)

For non-trivial changes, open an issue before submitting a pull request.

This helps ensure:
- Alignment with project goals
- Clear scope
- Efficient review

Small fixes (typos, obvious bugs) may skip this step.

---

### 2. Fork and Branch

- Fork the repository
- Create a dedicated branch
- Keep changes focused and minimal

One logical change per pull request.

---

### 3. Make Your Changes

When making changes:

- Prefer simple, readable solutions
- Avoid clever or opaque implementations
- Document behavior and intent
- Do not break existing workflows

Assume your code will be maintained by someone else.

---

### 4. Test What You Change

You are responsible for testing your contribution.

At minimum:
- Builds must complete
- Scripts must run
- Configuration must not break defaults

Untested changes will not be merged.

---

### 5. Submit a Pull Request

Your pull request should include:

- A clear description of what changes
- Why the change is necessary
- How it aligns with the manifesto
- Any trade-offs or limitations

Pull requests without justification will be rejected.

---

## Review Process

- Reviews are strict and intentional
- Feedback may be direct
- Revisions may be requested
- Rejection is not personal

All decisions are made in the interest of long-term stability and clarity.

---

## Decision Authority

The Campy Coyote maintainer(s):

- Interpret the manifesto
- Define project direction
- Have final say on merges

Consensus is valued, but coherence is required.

---

## Code Style and Standards

- Shell scripts must be POSIX-compliant unless justified
- Avoid unnecessary dependencies
- Follow existing project conventions
- Prefer explicitness over magic

Consistency matters more than personal preference.

---

## Documentation Contributions

Documentation is first-class.

Good documentation:
- Is concise
- Explains *why*, not just *how*
- Avoids assumptions
- Matches actual system behavior

Outdated documentation is considered a bug.

---

## Licensing

By contributing, you agree that your contributions:
- Are provided under the project’s applicable open-source licenses
- May be redistributed as part of Campy Coyote

Do not submit code you do not have the right to license.

---

## Final Note

Campy Coyote values contributors who:
- Think critically
- Respect constraints
- Take responsibility for their work

If that aligns with how you operate, your contributions are welcome.

---

**Stay sharp. Stay light. Survive anywhere.**

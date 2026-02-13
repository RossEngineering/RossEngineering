# RossEngineering

RossEngineering is a GitHub organisation used to house my **professional software engineering work**.

The repositories here focus on **clarity of intent, correctness of behaviour, and systems that remain understandable as they evolve**. This organisation exists to separate deliberate, portfolio-grade engineering from student work, experimentation, and hobby projects.

---

## What This Organisation Is For

RossEngineering repositories typically emphasise:

- Clear domain and system modelling
- Explicit boundaries and responsibilities
- API-first and backend-focused architectures
- Thoughtful evolution over feature accumulation
- Code that is intended to be read, reasoned about, and defended

These projects are not demos or exercises.  
They represent intentional work, built with longevity and maintainability in mind.

---

## Engineering Philosophy

Across all repositories, the same principles apply:

- Explicit behaviour over implicit magic  
- Correctness before optimisation  
- Clear separation of orchestration and execution  
- Extensibility without conditional sprawl  
- Preference for boring, predictable systems in production  

If a design decision cannot be explained simply, it probably is not finished yet.

---

## Governance & Standards

RossEngineering operates with a small but explicit set of organisational decisions and Architecture Decision Records (ADRs). These exist to ensure consistency, honesty, and long-term coherence.

### Organisation Decisions

High-level organisational posture is documented in:

- `docs/organisation-decisions.md`

This covers topics such as:
- licensing posture
- contribution expectations
- documentation philosophy
- CI expectations
- deployment assumptions
- public narrative and tone

These decisions apply across the organisation unless explicitly overridden.

---

### Architecture Decision Records (ADRs)

Formal decisions with long-term impact are captured as ADRs under `docs/adr/`.

Key ADRs include:

- **Repository Admission & Lifecycle Policy**  
  Defines the quality bar for repositories promoted into RossEngineering.

- **Testing & Quality Assurance Expectations**  
  Establishes testing as a first-class requirement.

- **Security Posture & Disclosure Policy**  
  Defines a proportional, responsible approach to security.

- **Versioning & Backward Compatibility Strategy**  
  Commits to conservative, respect-based versioning and deprecation.

- **Incubator Policy & Promotion Criteria**  
  Defines how early-stage projects mature within the organisation.

- **AI Usage Policy**  
  Documents how AI tools are used as collaborators, not substitutes for understanding.

Together, these records define *how* engineering decisions are made here, not just *what* is built.

---

## Repository Lifecycle

Repositories in RossEngineering generally follow this progression:

**Incubator → Promoted → Archived**

- *Incubator* repositories are intentional but incomplete
- *Promoted* repositories meet the organisation’s professional baseline
- *Archived* repositories remain visible and valuable, but are no longer active

Repositories are not moved back to personal accounts once promoted.

---

## Contribution Expectations

RossEngineering is not generally open to unsolicited contributions.

Contributions may be considered on a **case-by-case basis** and will always begin with discussion.  
This organisation prioritises architectural coherence over throughput.

See individual repositories for specific guidance.

---

## Use of AI

AI tools are used openly and deliberately within RossEngineering.

They are treated as **collaborative development tools**, not authorities.  
Nothing is shipped that is not fully understood and defensible without AI assistance.

Details are documented in the AI Usage Policy ADR.

---

## What This Organisation Signals

This organisation is intended to signal that its maintainer:

- values clarity over cleverness
- treats design decisions as first-class work
- understands trade-offs and long-term consequences
- uses modern tools responsibly
- prefers evolution over rewrites

---

## About

RossEngineering represents my work as a **professional software engineer**.

For experimentation, learning exercises, and informal projects, see my personal GitHub profile.

---

*Quiet honesty. Clear systems. Deliberate evolution.*

---

## Notepad Plus Plus Linux

The **Notepad Plus Plus Linux** repository is part of the RossEngineering organization, representing my work on porting the widely-used **Notepad++** text editor to Linux environments. This project follows the same engineering principles that underpin the rest of my repositories:

- Clear domain and system modelling
- Explicit boundaries and responsibilities
- API-first and backend-focused architectures
- Thoughtful evolution over feature accumulation

This repository is designed to be a high-quality, maintainable solution for users on Linux, bringing the powerful, extensible features of Notepad++ to a new platform. Like all projects under **RossEngineering**, it is built with longevity, correctness, and clarity in mind.

### Features

- Native Linux support for Notepad++ functionality.
- Optimized for performance and compatibility with various Linux distributions.
- Aiming for feature parity with the Windows version, with specific attention to Linux-native improvements.

### Contribution

As with all repositories under **RossEngineering**, contributions to the Notepad Plus Plus Linux project are handled on a **case-by-case basis**. Please start by discussing any proposed changes with the maintainers to ensure architectural coherence.

This repository adheres to the same [AI Usage Policy](docs/adr/ai-usage-policy.md), ensuring responsible integration of AI tools during development.

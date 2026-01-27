# RossEngineering — Organisational Decisions

This document captures **organisation-level decisions** made for RossEngineering that are **not formalised as ADRs**.

It exists to provide shared context, consistency, and intent across the organisation.  
Decisions recorded here are expected to evolve, but changes should be explicit and deliberate.

Where a topic is governed by an ADR, this document defers to that record.

---

## 1. Licensing

**Decision**  
Licensing is decided **on an ad hoc, per-repository basis**.

**Rationale**  
Projects within RossEngineering serve different purposes (portfolio, learning, reference implementations). A single licence policy would unnecessarily constrain future choices.

**Implications**
- Every repository must explicitly declare a licence
- Licence choice should align with the project’s intent
- Absence of a licence is considered incomplete

---

## 2. Contributions & Community

**Decision**  
RossEngineering is **not generally open to unsolicited contributions**.

Contributions may be accepted **case by case**, and will always begin with discussion.

**Rationale**  
Repositories prioritise deliberate design and learning progression. Unstructured contributions risk diluting architectural intent.

**Implications**
- Discussions are the first step for any proposed contribution
- Pull requests without prior alignment may be declined
- This is a portfolio-first, not crowd-sourced, organisation

---

## 3. Naming & Structure

**Decisions**
- Repository names use **PascalCase**
- Suffixes are used where appropriate (for example `.Platform`, `.Api`)
- Solution name must match repository name
- A shared namespace root is preferred

**Open Question**
- Template strategy remains intentionally undecided and will be revisited

**Rationale**  
Consistency reduces cognitive load and signals intentional design.

---

## 4. Documentation Philosophy

**Decision**  
Documentation should be **detailed and explicit**, serving as justification and evidence of prior thought.

**Rationale**  
Documentation is part of the engineering work, not an afterthought.  
Clear reasoning improves maintainability, onboarding, and long-term confidence.

---

## 5. CI & Automation

**Decision**  
Every repository must include CI with **build and test as a minimum baseline**.

**Rules**
- CI must pass on `main`
- Failure on `main` is not permitted

**Rationale**  
Automation enforces discipline and prevents silent regressions.

---

## 6. Deployment & Runtime Assumptions

**Decisions**
- Projects are not necessarily local-first
- Docker (or successor container technology) is mandatory for backend systems
- Desktop software must provide an installer or script
- Deployment documentation is provided as appropriate per project

**Rationale**  
Operational clarity is part of professional engineering, but requirements must fit the nature of the system.

---

## 7. PillBoi Status

**Decision**  
PillBoi remains on the personal account.

**Rationale**  
It is primarily an IoT tinkering project and requires unstructured experimentation time.  
Promotion will be reconsidered only if it becomes a deliberate, well-documented system.

---

## 8. Public Narrative

**Decision**  
RossEngineering adopts a stance of **quiet honesty**.

**Principles**
- No exaggerated claims
- No unnecessary disclaimers
- Let design quality speak for itself
- Learning is implied through structure, not advertised

---

## Summary Principle

Across all decisions, RossEngineering optimises for:

> **Clarity, correctness, and evolution over speed, novelty, or feature count.**

All future decisions should align with this principle.

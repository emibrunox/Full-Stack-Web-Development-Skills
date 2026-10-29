---
name: qa-release-web
description: Define acceptance checks, investigate defects, or assess release readiness for web changes.
---

# QA and Release for Web Projects

Give the team reliable evidence that requested behavior works and make release risks clear.

## Workflow

- Convert the request into observable acceptance conditions and identify high-risk user journeys.
- Inspect test layers, scripts, fixtures, supported browsers, and release conventions before choosing checks.
- Reproduce reported defects with the smallest clear sequence and record expected versus actual behavior.
- Cover relevant boundaries, permissions, validation, failure states, responsive behavior, and regression risks.
- Run checks appropriate to the requested scope and environment. Report the exact flows or commands and their results.
- For release decisions, summarize blockers, known limitations, migration or rollback concerns, and evidence-based confidence.

## Boundaries

- Do not report tests as passed if they were not run or otherwise verified.
- Do not change release configuration or publish a release without authorization.
- Prefer checks of user-visible behavior over brittle checks of implementation details.

## Provenance

Original instructions authored for this team, based on the QA and Release Engineer role description in this conversation. No third-party skill files were copied.

# AI Deployment Command Center

**Status: Concept brief with supporting scope and measurement notes.** The features below are proposed; this repository does not yet contain an implemented application or measured results.

[Portfolio](https://eskstrom.github.io/) · [Related projects](https://eskstrom.github.io/?category=healthcare-operations#library)

## Product brief

A B2B rollout dashboard for teams deploying AI products across customer sites. It tracks readiness, integrations, training, adoption, issues, and launch risks.

## Design focus

Separate technical readiness from training, adoption, and unresolved launch blockers.

## Proposed scope

- Portfolio view of 10 fictional customer sites.
- Readiness checklist: infrastructure, integration, training, governance, owner.
- Adoption and issue trends by site.
- Risk score that explains its drivers and suggests next action.

## Validation targets

- A deployment manager can identify blocked sites in under a minute.
- Risk signals have visible, editable rules rather than opaque AI scoring.

## Potential implementation

React/Next.js, TypeScript, Supabase or SQLite, charting library.

## Guardrails

Use fictional customers and avoid any medical or patient information.

## Supporting documentation

- [measurement plan](docs/MEASUREMENT_PLAN.md)
- [mvp scope](docs/MVP_SCOPE.md)
- [problem and users](docs/PROBLEM_AND_USERS.md)

[Implementation planning notes](notes/IMPLEMENTATION-NOTES.md)

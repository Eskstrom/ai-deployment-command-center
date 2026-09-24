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

<!-- portfolio-future-plans:start -->
## Future plans and PRD direction

*Planning review: 24 September 2026. These are proposed next steps, not completed work or measured outcomes.*

**Priority recommendation:** Retain as the enterprise adoption backlog.

Consolidate rollout readiness, feedback and launch controls into one focused deployment-management workflow.

### Next scope

- [ ] Define a deployment manager's decision across ten fictional customer sites, separating integration readiness from training and adoption.
- [ ] Specify owner, evidence, unresolved blocker and next action for each launch gate.
- [ ] Bring feedback classification and governance requirements into this PRD as proposed modules, without claiming they have been migrated.
- [ ] Prototype a blocked-site triage task before expanding dashboard scope.

### Validation and decision criteria

Measure blocked-site identification, actionability and handoff completeness in a user task. Define adoption denominators and time windows. Transparent editable rules should explain every readiness signal.
<!-- portfolio-future-plans:end -->

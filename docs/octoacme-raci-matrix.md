# OctoAcme — RACI Matrix

## Purpose
Clarify accountability and communication expectations across all project roles for key activities throughout the project lifecycle.

## RACI Key
| Letter | Meaning |
|---|---|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; final decision-maker (one per activity) |
| **C** | **Consulted** — provides input before or during the activity |
| **I** | **Informed** — kept up-to-date on outcomes |

## Role Abbreviations
| Abbreviation | Role |
|---|---|
| PM | Project Manager |
| PdM | Product Manager |
| Dev | Developer(s) |
| EM | Engineering Manager / Tech Lead |
| Des | Designer / UX Researcher |
| QA | Quality Assurance / Test Engineer |
| Sup | Customer Support / Customer Success |
| Stkh | Business Stakeholder / Sponsor |
| Sales | Sales / Solutions Engineer |

---

## Initiation Activities

| Activity | PM | PdM | Dev | EM | Des | QA | Sup | Stkh | Sales |
|---|---|---|---|---|---|---|---|---|---|
| Define problem statement | C | A/R | C | C | C | — | C | C | C |
| Identify success metrics | C | A/R | C | C | — | — | C | C | C |
| Stakeholder alignment meeting | R | R | — | C | — | — | — | A | — |
| Create Project One-pager | A/R | R | — | C | — | — | — | C | — |
| Go / no-go decision | C | C | — | C | — | — | — | A | — |
| Initial risk list | A/R | C | C | C | — | — | — | I | — |

---

## Planning Activities

| Activity | PM | PdM | Dev | EM | Des | QA | Sup | Stkh | Sales |
|---|---|---|---|---|---|---|---|---|---|
| Project kickoff meeting | A/R | R | R | R | R | R | I | I | I |
| Backlog creation & prioritization | C | A/R | C | C | C | C | C | C | C |
| Estimation (T-shirt / story points) | C | C | A/R | R | C | C | — | — | — |
| Define Definition of Done | C | C | R | A/R | C | R | — | — | — |
| Release plan & milestones | A/R | R | C | C | C | C | I | I | — |
| Initial test strategy | C | C | C | C | — | A/R | — | — | — |
| UX / design brief & scope | C | R | — | C | A/R | — | C | — | — |
| Risk register (initial) | A/R | C | C | C | — | C | — | I | — |
| Dependency identification | R | C | R | A/R | C | C | — | — | C |

---

## Execution Activities

| Activity | PM | PdM | Dev | EM | Des | QA | Sup | Stkh | Sales |
|---|---|---|---|---|---|---|---|---|---|
| Feature implementation | — | — | A/R | C | — | — | — | — | — |
| Technical design review | C | C | R | A/R | — | — | — | — | — |
| Design review & specs | C | C | R | C | A/R | — | — | — | — |
| Pull request review | — | — | A/R | R | — | — | — | — | — |
| Test case authoring | — | C | C | — | — | A/R | — | — | — |
| Manual / exploratory QA | C | C | C | — | C | A/R | — | — | — |
| Bug triage & prioritization | C | A | R | C | — | R | C | — | — |
| Daily standup facilitation | A/R | — | R | R | R | R | — | — | — |
| Risk register updates | A/R | C | C | C | — | C | — | I | — |
| Weekly status report | A/R | C | — | C | — | — | — | I | — |
| Blocker escalation | A/R | C | C | C | — | — | — | I | — |

---

## Release Activities

| Activity | PM | PdM | Dev | EM | Des | QA | Sup | Stkh | Sales |
|---|---|---|---|---|---|---|---|---|---|
| Pre-release checklist review | A/R | C | C | C | C | R | C | — | — |
| QA sign-off | C | C | — | C | — | A/R | — | — | — |
| Release notes authoring | R | R | C | C | — | C | C | I | C |
| Deployment to staging | C | — | R | A/R | — | C | — | — | — |
| Smoke tests (staging) | C | — | R | C | — | A/R | — | — | — |
| Deployment to production | C | — | R | A/R | — | C | — | I | — |
| Post-deploy verification | C | — | R | R | — | A/R | — | — | — |
| Release announcement | A/R | R | — | — | — | — | R | I | I |
| Incident response (if needed) | A/R | C | R | R | — | C | R | I | — |

---

## Retrospective Activities

| Activity | PM | PdM | Dev | EM | Des | QA | Sup | Stkh | Sales |
|---|---|---|---|---|---|---|---|---|---|
| Retrospective facilitation | A/R | C | R | R | R | R | — | — | — |
| Action item tracking | A/R | C | C | C | C | C | — | I | — |
| Process improvement backlog | R | A | C | C | — | C | — | — | — |

---

## Notes
- Each activity row must have exactly one **A** (Accountable).
- A role can be both **R** and **A** for the same activity (they do the work and own the outcome).
- Adjust this matrix at project kickoff to reflect the actual team composition — not all roles are present on every project.
- Store the project-specific RACI in the project repo alongside the Project Charter.

---

## Reference
- Full role descriptions: [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md)
- Project initiation activities: [`octoacme-project-initiation.md`](octoacme-project-initiation.md)
- Release activities: [`octoacme-release-and-deployment.md`](octoacme-release-and-deployment.md)

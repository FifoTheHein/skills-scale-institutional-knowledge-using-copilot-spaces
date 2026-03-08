# OctoAcme — Definition of Done (DoD)

## Purpose
Establish a shared, team-agreed standard for what "done" means so that all work items are completed consistently and quality is never ambiguous.

## Why It Matters
Without a clear Definition of Done, individual team members may apply different quality bars. This leads to rework, production incidents, and inconsistent experiences for customers. A shared DoD creates a reliable quality gate that every work item must pass before being considered complete.

---

## Standard Definition of Done

The following criteria apply to **all work items** (features, fixes, improvements) unless explicitly overridden at the project level.

### Code & Implementation
- [ ] Code implements the full acceptance criteria as defined in the issue or backlog item
- [ ] Code has been reviewed and approved by at least one other team member
- [ ] PR is linked to the corresponding issue or backlog item
- [ ] No unresolved review comments that affect correctness or security

### Testing
- [ ] Unit tests written and passing for all new logic
- [ ] Integration tests written and passing where applicable
- [ ] Manual QA completed for user-facing features (QA Engineer or developer self-review)
- [ ] No known regressions introduced
- [ ] Automated CI checks (tests, lint, security scans) are green

### Design & UX
- [ ] Implementation matches approved design specs (if a Designer was involved)
- [ ] Accessibility requirements met (keyboard navigation, screen reader support, color contrast)
- [ ] Responsive / multi-device behavior validated where applicable

### Documentation & Communication
- [ ] In-code documentation updated (README, docstrings, inline comments for complex logic)
- [ ] User-facing documentation updated if behavior changes
- [ ] Release notes entry drafted (for features and significant fixes)

### Deployment Readiness
- [ ] Feature is deployable (no blocking dependencies unresolved)
- [ ] Feature flags or configuration are documented if used
- [ ] No outstanding security vulnerabilities introduced (scans pass)

---

## Project-Level Overrides

Teams may adjust the DoD for a specific project by documenting exceptions in the project charter or planning docs. Common adjustments include:

| Adjustment | When it applies |
|---|---|
| Skip integration tests | Prototype / spike work with explicit PM sign-off |
| Skip design review | Backend-only or non-UI changes |
| Lightweight QA only | Low-risk config changes, documentation updates |
| Additional sign-off required | Regulated or high-stakes deployments |

---

## Sprint / Release DoD

In addition to the per-item DoD, the following must be true before a sprint or release is considered done:

- [ ] All committed items meet the item-level DoD above
- [ ] QA sign-off obtained from QA Engineer (or Product Manager if no dedicated QA)
- [ ] Risk register reviewed and updated
- [ ] Release notes finalized
- [ ] Stakeholders notified of what ships (or what is deferred)
- [ ] Retrospective scheduled (for sprint close) or completed (for release)

---

## DoD Review Cadence

- Review the DoD at the **start of each project** during kickoff planning.
- Revisit and update the DoD in **retrospectives** when quality gaps or process issues emerge.
- Document any agreed changes to the DoD in the project charter or planning docs.

---

## Reference

- Backlog item template: [`octoacme-project-planning.md`](octoacme-project-planning.md)
- QA roles and responsibilities: [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md)
- Release requirements: [`octoacme-release-and-deployment.md`](octoacme-release-and-deployment.md)

# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- QA sign-off obtained (QA Engineer completes checklist below)
- Designer UX validation completed for user-facing changes
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared
- Customer Support / Customer Success notified of upcoming changes

## QA Sign-off Checklist
- [ ] All acceptance criteria validated against the Definition of Done
- [ ] Manual / exploratory testing completed for high-risk flows
- [ ] No open critical or high-severity bugs
- [ ] Regression testing completed (automated and/or manual)
- [ ] Test summary documented and shared with PM and PdM
- [ ] QA sign-off confirmed: **Signed off by:** _______________ **Date:** _______________

## Deployment Checklist
- [ ] QA sign-off checklist completed (see above)
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support
- [ ] Customer Support briefed with release notes and known issues

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

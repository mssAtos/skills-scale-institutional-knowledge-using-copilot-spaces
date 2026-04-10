# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans — **Security Champion** confirms all findings are resolved or risk-accepted
- UX Designer has signed off on user-facing changes
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared
- **Support Lead** confirms support runbooks, FAQs, and escalation guides are complete (support-readiness sign-off)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Security Champion sign-off: open security findings resolved or risk-accepted
- [ ] Support Lead sign-off: runbooks, FAQs, and escalation guides published
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support — include Support Lead in the announcement chain

> See [Roles & Personas](octoacme-roles-and-personas.md) and [Role Interactions & RACI](octoacme-role-interactions-and-raci.md) for ownership of each step.

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

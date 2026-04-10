# OctoAcme Project Management Docs

## Overview

OctoAcme uses a structured, repeatable project management lifecycle: **Initiation → Planning → Execution → Release → Retrospective**. The approach is anchored in customer-first value delivery, iterative increments, and clear ownership. Every initiative begins with a **Project One-pager/Charter**, an initial risk list, and a high-level timeline before a go/no-go gate.

During **Planning**, approved work is broken into shippable increments with explicit acceptance criteria and estimates. The team defines a **Definition of Done**, maps dependencies in a **Risk Register** (impact, likelihood, owner, mitigation, status), and produces a milestone/release map.

**Execution & Tracking** relies on a project board (columns: Backlog → Ready → In Progress → In Review → QA → Done) and a PR workflow favoring small pull requests, CI checks (tests, linting, security scans), and at least one approval before merging. The team runs **daily standups**, a **weekly delivery sync**, and **sprint or milestone demos** to stay aligned.

**Release & Deployment** follows a checklist: passing CI/security scans, prepared release notes, a rollback plan, and staging smoke tests before production. After each release or milestone, a **Retrospective** captures learnings and produces owned, time-bound action items fed back into the backlog.

Core **roles** — Project Manager, Product Manager, Developer, and QA — each have defined responsibilities and communication patterns. Stakeholder updates are provided weekly or at milestones via a single source of truth, with a structured escalation path: team triage → PM → Product Lead → Sponsor for business-impacting issues.

---

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, lifecycle summary, and communication cadence |
| [Project Initiation Guide](octoacme-project-initiation.md) | Validating and authorizing new work: one-pager template, stakeholder alignment, go/no-go gate |
| [Project Planning](octoacme-project-planning.md) | Backlog creation, estimation, Definition of Done, risk/dependency mapping, release plan |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Project board, PR workflow, CI/QA practices, metrics, and blocker escalation |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk Register, risk lifecycle, stakeholder communication, escalation paths |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Release types, pre-release checklist, deployment steps, rollback playbook, release notes |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, running the session, tracking improvement action items |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed responsibilities, goals, and communication patterns for each core role |

> For detailed guidance on any process stage, refer to the linked document above.

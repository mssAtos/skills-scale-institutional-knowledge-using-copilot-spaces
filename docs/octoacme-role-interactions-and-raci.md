# OctoAcme — Role Interactions & RACI Matrix

This document maps key project lifecycle activities to the roles defined in [Roles & Personas](octoacme-roles-and-personas.md). Use it to clarify ownership, reduce handoff ambiguity, and ensure all required voices are consulted at the right time.

## RACI Key

| Code | Meaning |
|------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; must approve |
| **C** | **Consulted** — provides input before/during the activity |
| **I** | **Informed** — notified of outcome or progress |

## Roles Abbreviations

| Abbreviation | Role |
|---|---|
| PM | Project Manager |
| PdM | Product Manager |
| Dev | Developer(s) |
| UX | UX Designer |
| SC | Security Champion |
| BA | Business Analyst |
| SL | Support Lead |

---

## RACI Matrix

### 1 — Initiation

| Activity | PM | PdM | Dev | UX | SC | BA | SL |
|---|---|---|---|---|---|---|---|
| Draft Project One-pager / Charter | R | A | I | C | C | C | I |
| Identify and document stakeholders | R | C | I | I | I | C | C |
| Define success metrics | C | A | I | C | I | R | I |
| Create initial Risk Register | R | C | C | I | C | C | I |
| Go / No-go decision | I | A | I | I | I | I | I |
| Comms plan (internal & external) | R | C | I | I | I | C | C |

### 2 — Planning

| Activity | PM | PdM | Dev | UX | SC | BA | SL |
|---|---|---|---|---|---|---|---|
| Backlog creation & prioritisation | C | A | C | C | C | R | C |
| Write acceptance criteria / user stories | C | A | C | C | C | R | I |
| UX design & prototype review | I | A | C | R | I | C | I |
| Threat modelling for new features | I | C | C | I | R | I | I |
| Definition of Done (DoD) | C | A | R | C | C | C | C |
| Risk & dependency mapping | R | C | C | I | C | C | I |
| Release plan / milestone map | R | A | C | I | I | I | C |
| Support-readiness planning | I | C | I | I | I | I | R |

### 3 — Execution & Tracking

| Activity | PM | PdM | Dev | UX | SC | BA | SL |
|---|---|---|---|---|---|---|---|
| Feature implementation | I | I | R | C | C | C | I |
| Code review & PR approval | I | I | R | I | C | I | I |
| Security scan triage | I | I | C | I | R | I | I |
| UX validation / usability review | I | A | C | R | I | I | I |
| UAT coordination | C | A | C | I | I | R | I |
| Blocker escalation | R | C | C | I | C | I | I |
| Risk register updates | R | I | C | I | C | C | I |
| Demo / sprint review | R | A | R | R | C | C | C |

### 4 — Release & Deployment

| Activity | PM | PdM | Dev | UX | SC | BA | SL |
|---|---|---|---|---|---|---|---|
| Pre-release checklist sign-off | R | A | C | C | C | I | C |
| Security sign-off | I | I | C | I | R | I | I |
| Support-readiness review | C | I | C | I | I | I | R |
| Deploy to staging & smoke tests | I | I | R | I | C | I | I |
| Deploy to production | I | A | R | I | C | I | I |
| Stakeholder & support announcement | R | C | I | I | I | I | C |
| Rollback decision (if needed) | R | A | C | I | C | I | I |

### 5 — Retrospective & Continuous Improvement

| Activity | PM | PdM | Dev | UX | SC | BA | SL |
|---|---|---|---|---|---|---|---|
| Facilitate retrospective | R | C | C | C | C | C | C |
| Capture improvement action items | R | C | C | C | C | C | C |
| Review success metrics | C | R | I | C | I | C | I |
| Security posture review | I | I | C | I | R | I | I |
| Support-ticket trend analysis | I | C | I | I | I | I | R |
| Feed learnings into next backlog | C | R | C | C | C | C | C |

---

## Key Handoff Points

The following moments require explicit coordination between roles to avoid gaps:

| Handoff | From | To | What is handed over |
|---|---|---|---|
| Initiation → Planning | PdM + BA | Dev + UX | Prioritised problem statement, initial requirements, stakeholder list |
| Design approval | UX | Dev | Approved wireframes/specs with UX acceptance criteria |
| Threat model sign-off | SC | Dev | Approved threat model; open security items in Risk Register |
| Requirements freeze | BA | Dev + PdM | Finalised acceptance criteria; confirmed UAT plan |
| Pre-release security sign-off | SC | PM | Confirmation that open security findings are resolved or risk-accepted |
| Support-readiness sign-off | SL | PM | Runbooks, FAQs, training, and escalation guides are complete |
| Release announcement | PM + PdM | SL + stakeholders | Release notes, known issues, rollback contacts |
| Retrospective action items | PM | PdM + team | Owned, time-bound improvement tasks added to backlog |

---

## Tips for Using This Matrix

- Review the relevant RACI rows at the **start of each lifecycle phase** to confirm owners and consulted parties.
- If a role is missing (e.g., no dedicated UX Designer), the Product Manager or a Developer with UX knowledge should cover those responsibilities and note the gap in the Risk Register.
- For lightweight projects, collapse Consulted (C) meetings into existing standups or async check-ins.
- Keep this document updated when team structure changes.

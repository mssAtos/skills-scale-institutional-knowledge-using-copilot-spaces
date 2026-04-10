# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level → PM → Product Lead → Sponsor
- **Security escalation**: Security Champion triages finding → Security Champion + PM notify Security on-call → follow security incident runbook → post-incident blameless retrospective. For critical vulnerabilities, bypass PM and escalate directly to Security on-call.
- **Customer-impacting support escalation**: Support Lead flags issue → PM coordinates response → Product Lead if scope/roadmap impact → Sponsor for sustained service disruption. Support Lead provides initial customer communication while resolution is in progress.

> See [Roles & Personas](octoacme-roles-and-personas.md) for role definitions and [Role Interactions & RACI](octoacme-role-interactions-and-raci.md) for ownership during escalation activities.

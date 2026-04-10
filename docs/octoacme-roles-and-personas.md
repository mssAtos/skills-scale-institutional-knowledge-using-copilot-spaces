# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## UX Designer

### Role Summary
UX Designers ensure the product is usable, accessible, and aligned with user needs. They conduct research, create wireframes/prototypes, and validate designs with real users before and during development.

### Responsibilities
- Conduct user research and synthesise findings into actionable insights
- Create wireframes, prototypes, and high-fidelity designs for new features
- Define and document UX acceptance criteria alongside functional criteria
- Run usability testing and share results with the delivery team
- Maintain a design system or component library where applicable

### Goals
- Deliver experiences that are intuitive and accessible
- Reduce usability defects caught late in the cycle
- Ensure design decisions are grounded in evidence

### Typical Communication
- Sprint planning and review sessions (present designs, review implemented features)
- Design critique sessions and async Figma/design-tool comments
- Usability test result summaries shared with Product Manager and Developers

### Interactions with Existing Roles
- **Product Managers**: collaborate on problem framing, success metrics, and acceptance criteria; align on scope before each sprint.
- **Developers**: pair on design feasibility, component reuse, and accessibility requirements; review implementations against design specs.
- **Project Managers**: flag design-blocking dependencies and risk areas during weekly syncs; confirm UX validation milestones in the release plan.

---

## Security Champion

### Role Summary
The Security Champion embeds security thinking into the delivery lifecycle. They are not a dedicated security team; rather, a team member who advocates for secure coding practices, threat modelling, and timely remediation.

### Responsibilities
- Lead lightweight threat-modelling sessions for new features or significant changes
- Review architecture and design decisions for security implications
- Triage and prioritise security scan findings from CI/CD pipelines
- Coordinate with external security or compliance teams when escalation is needed
- Keep the team informed of relevant vulnerabilities, advisories, and policy updates

### Goals
- Prevent security issues from reaching production
- Reduce mean-time-to-remediate for identified vulnerabilities
- Build a security-aware culture within the delivery team

### Typical Communication
- Security notes in PR descriptions and design docs
- Weekly delivery sync — brief security status update
- Immediate escalation channel (Slack/Teams/email) for critical findings

### Interactions with Existing Roles
- **Developers**: pair on secure coding patterns; review PRs for security-sensitive changes; coordinate remediation of scan findings.
- **Product Managers**: advise on security trade-offs in prioritisation; flag compliance requirements that affect scope.
- **Project Managers**: report security risks to the Risk Register; confirm security sign-off is included in the release checklist.

---

## Business Analyst

### Role Summary
Business Analysts bridge business stakeholders and the delivery team. They translate business needs into clear, testable requirements and ensure delivered features meet intended outcomes.

### Responsibilities
- Elicit and document business requirements through workshops, interviews, and process analysis
- Translate requirements into user stories, use cases, and acceptance criteria
- Participate in backlog refinement to keep items well-defined and prioritised
- Validate that delivered features meet business expectations through UAT support
- Produce process/workflow diagrams and data-flow documentation as needed

### Goals
- Ensure the team builds the right thing for the right reasons
- Reduce rework caused by unclear or incomplete requirements
- Accelerate stakeholder sign-off by providing evidence of alignment

### Typical Communication
- Backlog refinement sessions with Product Manager and Developers
- Requirements documentation and decision logs shared with stakeholders
- UAT sign-off summaries provided to Project Manager before release

### Interactions with Existing Roles
- **Product Managers**: collaborate on problem statements and success metrics; co-own backlog prioritisation decisions.
- **Developers**: clarify acceptance criteria during sprint planning and mid-sprint; review implementation against documented requirements.
- **Project Managers**: provide requirements-readiness status for planning gates; flag scope changes that affect the timeline.

---

## Support Lead

### Role Summary
The Support Lead represents the support and operations perspective throughout the project. They ensure the team ships features that can be effectively supported and that support staff are ready before each release.

### Responsibilities
- Participate in planning to identify supportability gaps in proposed features
- Author and maintain support runbooks, FAQs, and escalation guides for new capabilities
- Coordinate support-readiness activities (training, documentation, tooling) before each release
- Surface recurring support issues and customer feedback to the Product Manager and delivery team
- Act as the primary escalation point for customer-impacting production issues

### Goals
- Ensure every release ships with complete support documentation
- Reduce time-to-resolution for customer-reported issues
- Close the feedback loop between support data and product decisions

### Typical Communication
- Planning sessions — advise on support complexity of new features
- Pre-release readiness review (confirm docs and training are complete)
- Post-release retrospective input (support ticket trends, customer sentiment)

### Interactions with Existing Roles
- **Product Managers**: share customer feedback and support-ticket trends to inform roadmap; align on communication plan for external-facing changes.
- **Developers**: request runbook inputs and troubleshooting guides for new/changed components; report production bugs for triage.
- **Project Managers**: confirm support-readiness milestone in the release checklist; escalate customer-impacting issues through the formal escalation path.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to [Role Interactions & RACI](octoacme-role-interactions-and-raci.md) for a full responsibility matrix across lifecycle phases.


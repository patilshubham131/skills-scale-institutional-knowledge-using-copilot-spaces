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

## Release Engineer

### Role Summary
Release Engineers manage release pipelines and the operational aspects of delivering changes to staging and production.

### Responsibilities
- Design and maintain CI/CD pipelines and release automation
- Coordinate deployments to staging/production and own rollback procedures
- Maintain release-runbooks and smoke-test scripts
- Validate release readiness (artifacts, migrations, config)
- Monitor post-deploy signals during rollout and lead quick mitigations

### Goals
- Ensure reliable, repeatable, and auditable releases
- Reduce release-related incidents and mean time to recover (MTTR)
- Improve deployment velocity without sacrificing safety

### Typical Communication
- Release schedule coordination with PM, Developers, and QA
- Post-deploy verification status in release channel
- Incident handoffs to on-call and engineering as needed

### Interactions / Handoffs
- Works with Developers to ensure build artifacts and migration steps are ready.
- Coordinates with QA to run and validate smoke tests in staging.
- Notifies Project Manager and Product Manager of release windows and risks.

---

## Program Lead

### Role Summary
Program Leads oversee multiple related projects, coordinate cross-team priorities, and make trade-off decisions across initiatives.

### Responsibilities
- Align roadmaps and prioritize resources across projects
- Resolve inter-project dependencies and sequencing conflicts
- Set program-level objectives and measure aggregated outcomes
- Advise Project Managers on risk prioritization and mitigation
- Escalate high-impact decisions to Product Leads and Sponsors

### Goals
- Maximize overall program impact and resource efficiency
- Reduce cross-team blocking and rework
- Ensure consistent strategic alignment across projects

### Typical Communication
- Program-level planning cadences and roadmap reviews
- Cross-team dependency review meetings
- Periodic stakeholder briefings for sponsors and leadership

### Interactions / Handoffs
- Works with Project Managers to reallocate capacity when priorities shift.
- Coordinates with Product Managers to balance feature trade-offs across teams.

---

## UX Researcher

### Role Summary
UX Researchers design and run research to inform product decisions, validate designs, and provide user-centered acceptance criteria.

### Responsibilities
- Define research plans and recruit participants
- Conduct usability tests, interviews, and surveys
- Synthesize findings into actionable recommendations
- Validate acceptance criteria for UX and accessibility
- Share research outputs with Product, Design, and Engineering

### Goals
- Reduce usability risk and increase product adoption
- Ensure features meet user needs and accessibility standards

### Typical Communication
- Research findings shared during planning and design reviews
- Collaboration sessions with Product Managers and Designers
- Annotations in PRs or feature specs for usability criteria

### Interactions / Handoffs
- Partners with Product Managers to shape success metrics and acceptance criteria.
- Works with Developers and QA to verify UX-related acceptance during implementation.

---

## Security Champion

### Role Summary
Security Champions embed security practices into delivery teams and act as the first line for triaging security findings.

### Responsibilities
- Participate in threat modeling and design reviews
- Run or ensure security scans in CI are configured and acted upon
- Triage security findings and coordinate with Security on-call
- Advocate secure-by-default patterns in code and infra
- Maintain a backlog of security-related improvements

### Goals
- Reduce security vulnerabilities introduced in delivery
- Ensure timely remediation of critical security findings

### Typical Communication
- Security findings reported via issue trackers with triage notes
- Regular syncs with Security team or on-call for escalations
- Guidance and checklists for Developers in PRs

### Interactions / Handoffs
- Works with Developers to fix vulnerabilities and with Release Engineers to ensure fixes are deployed.
- Escalates severe issues to Project Manager and Product Lead when business impact is high.

---

## Vendor / Partner Liaison

### Role Summary
Vendor/Partner Liaisons manage third-party relationships, contract-related deliverables, and integration points.

### Responsibilities
- Manage vendor onboarding, SLAs, and integration checkpoints
- Track vendor deliverables, support paths, and incident procedures
- Surface vendor-related risks and coordinate mitigations
- Maintain contact lists and escalation paths for partners

### Goals
- Reduce integration friction and dependency risk
- Ensure vendor commitments are met and clearly communicated

### Typical Communication
- Status updates to Project Manager and Product Lead regarding vendor work
- Coordination meetings with vendor technical contacts
- Documentation of vendor integration steps and support expectations

### Interactions / Handoffs
- Works with Project Managers to schedule vendor-dependent milestones.
- Notifies Product Managers and QA of third-party testing requirements.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

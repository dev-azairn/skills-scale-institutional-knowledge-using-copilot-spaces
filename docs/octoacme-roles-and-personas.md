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

## QA Lead / Test Owner

### Role Summary
The QA Lead owns the test strategy, quality gates, and release readiness for a project. They partner closely with Developers and Project Managers to ensure that features meet acceptance criteria before release.

### Responsibilities
- Define and maintain the overall test strategy and quality standards
- Own test plans, test cases, and regression suites
- Establish quality gates and release readiness criteria
- Coordinate testing activities across development sprints
- Report defect trends, coverage gaps, and release risks
- Drive root-cause analysis on escaped defects

### Goals
- Prevent defects from reaching production
- Achieve and maintain target test coverage levels
- Reduce time spent on regression through automation
- Ensure releases are stable and meet acceptance criteria

### Typical Communication
- Sprint planning and review to align on testable stories
- Defect triage meetings with Developers and Project Managers
- Release readiness sign-off reports shared with Stakeholders
- Continuous coordination with Developers on test environments and build quality

### Interactions with Existing Roles
- **Developers**: collaborates on testability, reviews acceptance criteria, and pairs on automation
- **Project Managers**: reports quality status and flags risks to the release schedule
- **Product Managers**: confirms acceptance criteria are testable and complete
- **Stakeholders**: communicates release readiness and known risks before go-live

---

## Delivery Lead / Engineering Lead

### Role Summary
The Delivery Lead coordinates technical delivery across one or more teams. They bridge the gap between engineering implementation details and project-level planning, ensuring that technical commitments are realistic and dependencies are managed.

### Responsibilities
- Coordinate cross-team technical dependencies and integration points
- Facilitate technical trade-off discussions between engineering and product
- Track and communicate delivery risks stemming from architecture or implementation complexity
- Support capacity planning and sprint-level estimation
- Escalate technical blockers to Project Managers and stakeholders as needed
- Drive engineering process improvements and standards adoption

### Goals
- Ensure technical delivery aligns with project timelines and quality expectations
- Reduce delivery risk through proactive dependency management
- Improve team throughput and predictability

### Typical Communication
- Daily or weekly syncs with Developers and Project Managers
- Technical design reviews and architecture decision records
- Engineering status inputs to project status reports
- Escalation memos when technical blockers threaten milestones

### Interactions with Existing Roles
- **Developers**: provides guidance, removes blockers, and helps maintain coding and delivery standards
- **Project Managers**: supplies technical input to schedules, risks, and resource planning
- **Product Managers**: advises on technical feasibility and trade-offs during backlog refinement
- **QA Lead**: coordinates on environment readiness, build pipelines, and release quality gates
- **Stakeholders**: explains technical constraints and progress in accessible terms

---

## Stakeholder Champion

### Role Summary
The Stakeholder Champion represents a key business group or user segment. They ensure that the priorities and needs of their constituency are visible to the product and project team, and they help validate decisions and drive adoption.

### Responsibilities
- Represent the needs, constraints, and priorities of a specific stakeholder group
- Participate in backlog reviews and provide business validation of proposed solutions
- Communicate project progress and decisions back to their business group
- Facilitate access to subject matter experts and end users for research or testing
- Champion adoption of delivered features within their group

### Goals
- Ensure the delivered product meets the real needs of their stakeholder group
- Accelerate adoption and realization of business value
- Reduce rework caused by misunderstood requirements

### Typical Communication
- Regular check-ins with Product Managers on roadmap priorities
- Participation in sprint reviews and user acceptance testing
- Internal announcements and change management communications within their group

### Interactions with Existing Roles
- **Product Managers**: provides business context and validates prioritization decisions
- **Project Managers**: surfaces business risks or schedule concerns from the stakeholder side
- **Developers**: participates in user acceptance testing and provides real-world feedback
- **QA Lead**: assists with user acceptance test scenarios and sign-off

---

## Support / Operations Representative

### Role Summary
The Support / Operations Representative ensures that projects consider operational readiness, supportability, and post-release sustainability. They bring feedback from incidents and support queues back into the development process.

### Responsibilities
- Provide input on operational readiness requirements (monitoring, alerting, runbooks)
- Review releases for supportability and identify on-call risks
- Feed post-release incident data and support trends back to the team
- Participate in release planning to identify operational dependencies
- Collaborate on incident response and post-mortems

### Goals
- Ensure new releases are stable and supportable from day one
- Reduce incident volume and mean time to recovery
- Close the feedback loop between production issues and backlog priorities

### Typical Communication
- Release readiness reviews with Project Managers and QA Lead
- Incident reports and post-mortem documents shared with Developers and Delivery Lead
- Regular support metrics shared with Product Managers to inform prioritization

### Interactions with Existing Roles
- **Developers**: collaborates on observability, error handling, and runbook documentation
- **Project Managers**: flags operational risks that could affect release timelines or post-launch stability
- **Product Managers**: provides data on support burden to inform prioritization of reliability work
- **QA Lead**: coordinates on production-like testing environments and release acceptance criteria
- **Stakeholders**: communicates known operational limitations or caveats at release

---

## Security / Compliance Reviewer

### Role Summary
The Security / Compliance Reviewer advises the team on security requirements, risk mitigation, and regulatory compliance. They participate in key checkpoints to ensure that deliverables meet organizational and legal standards before release.

### Responsibilities
- Review designs, features, and implementations for security and compliance risk
- Define and communicate security requirements and acceptance criteria
- Conduct or coordinate security assessments, penetration testing, and audits
- Maintain a risk register for security and compliance findings
- Approve or escalate items that require exception handling or risk acceptance

### Goals
- Prevent security vulnerabilities and compliance violations from reaching production
- Embed security considerations early in the development lifecycle (shift left)
- Ensure the organization can demonstrate compliance to auditors and regulators

### Typical Communication
- Design review participation during initiation and planning phases
- Security findings reports shared with Delivery Lead, Project Managers, and Developers
- Compliance checkpoint sign-offs at release milestones
- Escalation to leadership when high-severity risks are identified

### Interactions with Existing Roles
- **Developers**: provides secure coding guidance and reviews implementations for vulnerabilities
- **Project Managers**: communicates compliance requirements and approval gates that affect timelines
- **Product Managers**: advises on security trade-offs and regulatory constraints during backlog prioritization
- **QA Lead**: coordinates on security test cases and penetration testing activities
- **Stakeholders**: communicates material compliance risks and required mitigations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.


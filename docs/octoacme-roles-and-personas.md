# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles may be combined or tailored to the size and needs of a team, but ownership for each responsibility should remain explicit.

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

## Executive Sponsors

### Role Summary
Executive Sponsors provide strategic direction and ensure an initiative remains aligned with organizational priorities. They own sponsorship of the business case and provide timely decisions or escalation support when issues exceed the delivery team's authority.

### Responsibilities
- Confirm strategic alignment and champion the initiative
- Help secure organizational support and resources
- Resolve or escalate high-impact risks and cross-organizational blockers
- Make or obtain decisions on major scope, priority, and investment trade-offs

### Interactions with Existing Roles
- Partner with the Product Manager on desired outcomes and priority trade-offs
- Work with the Project Manager on business-impacting risks, escalations, and decision timing
- Provide context and remove organizational barriers for Developers without directing day-to-day implementation

### Typical Communication
- Milestone reviews, sponsor updates, and escalations
- Decision reviews for significant scope, funding, or priority changes

---

## UX / Product Designers and User Researchers

### Role Summary
Designers and researchers bring user needs and usability evidence into discovery, design, and validation so that solutions are useful, accessible, and understandable.

### Responsibilities
- Plan and conduct user research or usability evaluations as appropriate
- Create and maintain user flows, interaction designs, and design specifications
- Identify accessibility and usability considerations
- Share research findings and design rationale with the team

### Interactions with Existing Roles
- Collaborate with the Product Manager to refine user problems, outcomes, and acceptance criteria
- Work with Developers to assess feasibility and clarify design details during implementation
- Coordinate with QA / Test Engineers to make usability and accessibility expectations verifiable
- Share findings with the Project Manager to inform plans, dependencies, and risks

### Typical Communication
- Discovery and design reviews, research readouts, and design documentation
- Ongoing collaboration with product, engineering, and QA during delivery

---

## QA / Test Engineers

### Role Summary
QA / Test Engineers help the team build confidence in product quality by defining and executing appropriate test approaches and communicating quality risks.

### Responsibilities
- Develop test strategies and test plans based on requirements and risk
- Validate acceptance criteria and important user flows
- Coordinate or perform integration, regression, and release smoke testing as appropriate
- Report defects and quality risks clearly, with reproducible details

### Interactions with Existing Roles
- Collaborate with Developers throughout implementation on testability, defects, and coverage
- Align with the Product Manager on acceptance criteria and feature behavior
- Coordinate with the Project Manager on test dependencies, readiness, and schedule risks
- Work with Operations / Support / Service Owners on operational checks and release readiness

### Typical Communication
- Test plans, defect reports, CI results, and release-readiness updates
- Participation in planning, reviews, and quality discussions

---

## Data / Analytics Leads

### Role Summary
Data / Analytics Leads ensure that product outcomes can be measured with trustworthy data and that teams can use evidence to assess impact.

### Responsibilities
- Translate success metrics into instrumentation and reporting needs
- Advise on event definitions, data quality, privacy, and measurement limitations
- Validate data collection and analysis, and report findings
- Help teams interpret results and identify follow-up questions

### Interactions with Existing Roles
- Partner with the Product Manager to define outcome measures and interpret product impact
- Work with Developers to implement and verify instrumentation
- Coordinate with QA / Test Engineers on validating data behavior where relevant
- Share progress and findings with the Project Manager and stakeholders so plans and decisions reflect evidence

### Typical Communication
- Metric definitions, dashboards, data-quality checks, and outcome reviews

---

## Operations / Support / Service Owners

### Role Summary
Operations, Support, and Service Owners help ensure delivered changes can be operated and supported reliably, and bring customer and service feedback back to the delivery team.

### Responsibilities
- Define or advise on monitoring, alerting, support, and operational readiness needs
- Prepare support teams and service documentation for relevant changes
- Identify reliability, capacity, and operational risks
- Participate in incident response and contribute operational learning where applicable

### Interactions with Existing Roles
- Partner with Developers and QA / Test Engineers on operability requirements, monitoring, and release checks
- Coordinate with the Project Manager on launch planning, support readiness, and escalations
- Share customer and operational feedback with the Product Manager to inform prioritization and product decisions
- Engage the Executive Sponsor through established escalation paths for significant business-impacting service issues

### Typical Communication
- Readiness reviews, runbooks, service dashboards, support briefings, and incident updates

---

## Security / Privacy Partners

### Role Summary
Security / Privacy Partners advise teams on security, privacy, and compliance requirements and help identify and manage related risks.

### Responsibilities
- Identify applicable security, privacy, and compliance requirements
- Review designs, data handling, and risk mitigations at appropriate points
- Recommend controls and verification activities
- Escalate material risks through the appropriate organizational process

### Interactions with Existing Roles
- Work with Developers and QA / Test Engineers to incorporate and verify relevant controls
- Advise the Product Manager on privacy and security implications of product choices
- Coordinate with the Project Manager to track risks, dependencies, and review milestones
- Involve the Executive Sponsor or designated decision-makers when significant residual risks require business-level decisions

### Typical Communication
- Risk reviews, security or privacy assessments, control guidance, and release consultations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Adapt role assignments to the team; combining roles does not remove the need to identify an accountable owner for each responsibility.

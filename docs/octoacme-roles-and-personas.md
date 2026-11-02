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

## Executive Sponsors / Business Owners

### Role Summary
Executive Sponsors or Business Owners provide strategic direction and organizational support for an initiative. They are accountable for ensuring the work remains aligned with business goals and for decisions that exceed the delivery team's authority.

### Responsibilities
- Confirm strategic alignment and expected business outcomes
- Secure or approve funding, staffing, and other organizational resources
- Make or escalate high-impact scope and priority decisions
- Resolve organizational blockers that the project team cannot address

### Interactions with Existing Roles
- Partner with the Product Manager to align outcomes and major priority decisions
- Work with the Project Manager on governance, resource constraints, and escalations
- Consult stakeholders and communicate significant decisions to them

### When to Engage
Engage this role when strategic alignment, significant resources, or decisions beyond the team's delegated authority are involved. The role may be combined with another leadership role on smaller initiatives.

---

## Business Analysts

### Role Summary
Business Analysts translate business needs into clear requirements, workflows, and decision-ready information for the delivery team.

### Responsibilities
- Elicit and document business needs, workflows, and constraints
- Analyze requirements, dependencies, and impacts across processes
- Help define scope and testable acceptance criteria
- Keep requirements and decisions clear as the work evolves

### Interactions with Existing Roles
- Work with the Product Manager and stakeholders to clarify needs and refine scope
- Coordinate with the Project Manager to surface dependencies and requirement-related risks
- Explain requirements to Developers and QA/Testing so implementation and validation address the intended need

### When to Engage
Engage this role when requirements span multiple stakeholders, workflows, or systems, or need structured analysis. The Product Manager or another team member may cover these activities on smaller projects.

---

## Technical Leads / Architects

### Role Summary
Technical Leads or Architects guide technical design and help the team make coherent implementation and integration decisions.

### Responsibilities
- Lead technical design and document significant architecture decisions
- Identify technical risks, integration points, and dependencies
- Advise on feasibility, sequencing, and maintainability
- Support engineering quality through design and code reviews

### Interactions with Existing Roles
- Collaborate with Developers on implementation choices, reviews, and technical risk mitigation
- Advise the Product Manager on feasibility and technical trade-offs
- Coordinate with the Project Manager on dependencies, sequencing, and delivery risks
- Work with QA/Testing to ensure the technical approach supports effective validation

### When to Engage
Engage this role when work has significant architecture, integration, scalability, or cross-team implications. The role may be filled by a Developer for smaller or well-understood changes.

---

## UX Researchers / Product Designers

### Role Summary
UX Researchers and Product Designers help teams understand user needs and create usable, accessible experiences that address them.

### Responsibilities
- Research user needs, context, and usability challenges
- Design user flows, interaction patterns, and interface specifications
- Validate proposed experiences through research or usability testing
- Identify accessibility and usability considerations early

### Interactions with Existing Roles
- Partner with the Product Manager to connect user evidence to product goals and priorities
- Share designs and research findings with Developers to guide implementation
- Work with QA/Testing to include relevant usability and accessibility checks
- Coordinate with stakeholders and the Project Manager on research timing and review needs

### When to Engage
Engage these roles when changes affect user journeys, interfaces, or accessibility, or when user needs are uncertain. A single person may cover both research and design on smaller projects.

---

## Security / Privacy Leads

### Role Summary
Security and Privacy Leads advise teams on protecting systems and data and meeting applicable security and privacy expectations.

### Responsibilities
- Identify security and privacy requirements, risks, and review checkpoints
- Advise on appropriate controls and data handling
- Review material security or privacy changes and document recommendations
- Escalate significant risks through the appropriate organizational channels

### Interactions with Existing Roles
- Work with Developers on secure implementation and risk mitigation
- Coordinate with QA/Testing on verification of security and privacy requirements
- Advise the Product Manager on user and product impacts of controls or risks
- Work with the Project Manager to track review dependencies and escalate unresolved risks; involve the Executive Sponsor / Business Owner when a decision exceeds the team's authority

### When to Engage
Engage this role when work handles sensitive data, changes security boundaries, introduces material risk, or requires specialist review. The need and review points should be assessed during planning, not deferred until release.

---

## Release / Operations (SRE) Leads

### Role Summary
Release and Operations Leads prepare services and teams to deploy, monitor, support, and recover changes in production.

### Responsibilities
- Define operational readiness, deployment, and rollback requirements
- Ensure monitoring, alerting, and support handoffs are prepared
- Coordinate release verification and incident response readiness
- Identify operational risks and recommend mitigations

### Interactions with Existing Roles
- Coordinate with Developers on deployment design, observability, and operational ownership
- Work with QA/Testing on smoke tests and release verification
- Partner with the Project Manager on release timing, dependencies, and communications
- Inform the Product Manager and stakeholders of operational constraints or customer-impacting incidents

### When to Engage
Engage this role when a change affects production services, deployment procedures, support readiness, or service reliability. In smaller teams, Developers may own these responsibilities with clear operational handoff.

---

## Data / Analytics Leads

### Role Summary
Data and Analytics Leads help teams define how outcomes will be measured and ensure relevant data is collected and interpreted appropriately.

### Responsibilities
- Translate success metrics into measurement and instrumentation requirements
- Advise on data quality, definitions, and reporting
- Validate analysis and outcome reporting after delivery
- Identify measurement limitations and communicate them clearly

### Interactions with Existing Roles
- Partner with the Product Manager to define success measures and interpret results
- Coordinate with Developers on instrumentation and data collection
- Work with the Project Manager to include measurement dependencies and findings in plans and status reporting
- Consult stakeholders on reporting needs and interpretation

### When to Engage
Engage this role when success depends on new instrumentation, complex analysis, or shared metric definitions. The Product Manager or another team member may handle straightforward measurement.

---

## Customer Support / Change Leads

### Role Summary
Customer Support and Change Leads prepare support teams and users for changes and help the organization adopt new processes or capabilities.

### Responsibilities
- Assess customer and operational impacts of changes
- Prepare support guidance, training, and adoption materials
- Coordinate readiness and feedback channels for affected users
- Track recurring issues and communicate them to the delivery team

### Interactions with Existing Roles
- Coordinate with the Project Manager on rollout timing, stakeholder communications, and readiness
- Work with the Product Manager to align adoption support with user needs and product changes
- Share known issues and support requirements with Developers and QA/Testing before release
- Gather stakeholder and customer feedback and route it to the relevant product and delivery owners

### When to Engage
Engage this role when a change affects customer-facing workflows, support needs, or how teams work. The role may be combined with a stakeholder or support representative for smaller changes.

---

## Applying Roles to a Project

- These personas describe responsibilities, not mandatory separate positions. Assign only the roles needed for the project's scope, risk, and complexity; one person may cover multiple roles when appropriate.
- Identify an owner for each needed responsibility during planning, including who makes decisions, who provides input, and how unresolved issues are escalated.
- Make handoffs and review points explicit in the plan, especially for requirements, security and privacy, operational readiness, and outcome measurement.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

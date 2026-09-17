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

## Security and Compliance Leads

### Role Summary
Security and Compliance Leads ensure that project decisions, designs, and releases meet applicable security, privacy, regulatory, and internal policy requirements. They provide specialist guidance without replacing the delivery ownership of the Project Manager or the product decisions of the Product Manager.

### Responsibilities
- Identify security, privacy, and compliance requirements during initiation and planning
- Review designs, data flows, dependencies, and release plans for security and compliance risks
- Define or approve required controls, threat mitigations, and evidence
- Record security and compliance risks in the risk register and recommend escalation when needed
- Partner with QA and developers to include security checks in testing and CI
- Provide release approval or documented exceptions when required by policy

### Goals
- Reduce preventable security and compliance risks
- Make security and privacy requirements clear early enough to avoid delivery delays
- Ensure releases have appropriate controls, evidence, and accountable risk decisions

### Interaction with Existing Roles
- Works with the Project Manager to schedule reviews, track risks, and escalate unresolved issues
- Works with the Product Manager to translate regulatory and customer trust requirements into prioritized acceptance criteria
- Advises developers and the Technical Architect on secure design, implementation, and integration choices
- Coordinates with QA on security test coverage and release evidence
- Provides stakeholders and sponsors with risk-based recommendations and escalation status

### Typical Communication
- Security and compliance reviews during planning and before release
- Risk-register updates and exception decisions
- Security findings in design documents, issue trackers, and release checklists

---

## Technical Architects

### Role Summary
Technical Architects guide system design and technical decisions so that solutions are maintainable, scalable, secure, and aligned with platform and integration standards. They provide technical direction while developers remain responsible for implementation details and code ownership.

### Responsibilities
- Define architecture options, constraints, and recommended technical approaches
- Document significant technical decisions and integration patterns
- Identify technical dependencies, scalability concerns, and migration needs
- Review designs and implementation plans for consistency with agreed architecture
- Support estimation by clarifying complexity, interfaces, and technical risks
- Collaborate with Security and Compliance Leads on secure architecture and with QA on testability and operational readiness

### Goals
- Enable consistent, sustainable technical decisions
- Reduce rework caused by unclear interfaces or hidden dependencies
- Balance delivery speed with reliability, maintainability, and future change

### Interaction with Existing Roles
- Works with the Project Manager to surface technical dependencies, risks, milestones, and decision points
- Works with the Product Manager to explain technical trade-offs and their impact on customer outcomes and scope
- Partners with developers through design reviews and implementation guidance without taking over day-to-day ownership
- Coordinates with Security and Compliance Leads to incorporate required controls
- Collaborates with QA to ensure architecture supports integration, end-to-end, and operational testing

### Typical Communication
- Architecture decision records and technical design reviews
- Dependency mapping during planning
- Design discussions with developers, Security and Compliance Leads, and QA

---

## UX Researchers and Designers

### Role Summary
UX Researchers and Designers represent user needs in product discovery and delivery. They generate evidence about user problems and create experiences that are usable, accessible, and consistent with the product goals.

### Responsibilities
- Plan and conduct user research, interviews, usability testing, and discovery activities
- Translate research findings into user journeys, interaction designs, and testable requirements
- Define usability and accessibility considerations with the Product Manager and delivery team
- Maintain design artifacts and communicate design rationale
- Validate prototypes and delivered experiences against user needs and acceptance criteria
- Identify experience risks and recommend iterative improvements

### Goals
- Ensure solutions address validated user problems
- Improve usability, accessibility, and customer satisfaction
- Reduce delivery rework by validating experience decisions early

### Interaction with Existing Roles
- Works with the Product Manager to refine problem statements, personas, priorities, and success measures
- Works with the Project Manager to schedule research, design reviews, usability testing, and stakeholder decisions
- Partners with developers and the Technical Architect to ensure designs are feasible and accurately implemented
- Collaborates with QA to define user-facing acceptance criteria and accessibility checks
- Shares evidence and recommendations with stakeholders without replacing the Product Manager’s prioritization accountability

### Typical Communication
- Research plans, findings, and usability-test readouts
- Design critiques, prototypes, and user-flow documentation
- Acceptance-criteria reviews with product, engineering, and QA

---

## Data and Analytics Leads

### Role Summary
Data and Analytics Leads ensure that projects define measurable outcomes, collect trustworthy signals, and use evidence to guide decisions. They connect product goals to instrumentation, reporting, and post-release evaluation.

### Responsibilities
- Translate project goals into measurable indicators, event definitions, and reporting requirements
- Establish data quality, privacy, ownership, and access expectations
- Partner with developers to define and validate instrumentation
- Build or coordinate dashboards and analysis for delivery and post-release monitoring
- Analyze outcomes and communicate insights, limitations, and recommendations
- Identify metric risks such as missing data, biased samples, or conflicting definitions

### Goals
- Make project outcomes observable and decision-ready
- Ensure success metrics are reliable, understood, and linked to customer value
- Enable teams to learn from releases and adjust priorities based on evidence

### Interaction with Existing Roles
- Works with the Product Manager to define success metrics and interpret product impact
- Works with the Project Manager to include analytics dependencies, milestones, and reporting in the delivery plan
- Collaborates with developers and the Technical Architect on instrumentation, data flows, and operational dashboards
- Partners with QA to validate event behavior and data quality in test environments
- Reports results and caveats to stakeholders so that release and follow-up decisions are evidence-informed

### Typical Communication
- Metric definitions and instrumentation plans
- Dashboards, release-readout reports, and decision summaries
- Data-quality reviews with product, engineering, QA, and stakeholders

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

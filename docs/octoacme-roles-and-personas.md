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

## Additional Personas

### Delivery Lead

#### Role Summary
Delivery Leads coordinate day-to-day delivery across multiple squads, manage sprint commitments, oversee release readiness, and maintain critical delivery artifacts.

#### Responsibilities
- Coordinate day-to-day delivery across multiple squads
- Manage sprint commitments and velocity tracking
- Oversee release readiness and deployment coordination
- Maintain delivery timeline and key artifacts (release checklist, deployment plan)
- Identify and escalate cross-team dependencies

#### Goals
- Ensure predictable, on-time delivery of commitments
- Reduce handoff delays and cross-team friction
- Maintain visibility into delivery health and risks

#### Typical Interactions
- Works closely with **PM** on scheduling and prioritization
- Aligns with **PdM** on scope and acceptance criteria
- Collaborates with **Engineering Managers** on capacity and blockers
- Partners with **QA** on acceptance criteria and release gating

---

### Engineering Manager

#### Role Summary
Engineering Managers focus on team health, capacity planning, technical growth, and escalation of technical risks. They partner with product and delivery leadership on resource trade-offs.

#### Responsibilities
- Plan team capacity and manage resource allocation
- Prioritize and manage technical debt alongside feature work
- Mentor and develop team members
- Identify and escalate technical risks and blockers
- Partner on technical design and architecture decisions

#### Goals
- Build a healthy, productive, and growing team
- Reduce technical debt and improve code quality
- Enable predictable velocity and risk mitigation

#### Typical Interactions
- Collaborates with **PM/Delivery Lead** on resourcing and capacity
- Works with **Developers** on technical design, code reviews, and mentoring
- Partners with **Product** on trade-offs between features and technical work

---

### UX Researcher / Designer

#### Role Summary
UX Researchers and Designers drive user research, synthesize findings into actionable insights, and create prototypes and acceptance criteria focused on usability and user outcomes.

#### Responsibilities
- Conduct user research and synthesize findings
- Create prototypes, wireframes, and design specifications
- Define user acceptance criteria focused on usability
- Collaborate on design reviews and iterations
- Validate solutions through user testing

#### Goals
- Ensure solutions are usable and meet user needs
- Reduce rework by catching usability issues early
- Drive data-informed design decisions

#### Typical Interactions
- Partners with **PdM** on defining user outcomes and success metrics
- Collaborates with **Developers** on implementation feasibility
- Works with **QA** on usability validation and acceptance testing

---

### Product Analyst

#### Role Summary
Product Analysts define success metrics, instrument products for data collection, run experiments, and provide post-release analysis to inform product decisions.

#### Responsibilities
- Define and track success metrics for features and projects
- Instrument analytics and set up tracking
- Design and run experiments (A/B tests, etc.)
- Conduct post-release analysis and impact assessment
- Report on key performance indicators (KPIs)

#### Goals
- Enable data-driven decision-making and prioritization
- Measure and demonstrate product impact
- Continuously optimize for user value and business outcomes

#### Typical Interactions
- Works with **PdM** to set measurable goals and success criteria
- Collaborates with **Developers** to add instrumentation and tracking
- Reports to **PM** on progress toward metrics and KPIs

---

### Platform / Infrastructure Owner

#### Role Summary
Platform and Infrastructure Owners maintain shared platform services, approve infrastructure changes, and manage capacity and reliability constraints that affect multiple teams.

#### Responsibilities
- Maintain and evolve shared platform services and APIs
- Approve infrastructure changes and scaling decisions
- Manage capacity planning and reliability constraints
- Coordinate service dependencies across teams
- Ensure compliance with operational and security policies

#### Goals
- Provide reliable, scalable infrastructure for product teams
- Minimize platform-related blockers and incidents
- Optimize for cost, performance, and compliance

#### Typical Interactions
- Coordinates with **Delivery Lead** on deployment windows and release planning
- Collaborates with **Engineering Managers** on technical dependencies and capacity
- Partners with **Security/DevOps** on compliance and operational readiness

---

### DevOps / Release Engineer

#### Role Summary
DevOps and Release Engineers manage CI/CD pipelines, automate deployments, define rollback strategies, and perform production verifications to enable safe, reliable releases.

#### Responsibilities
- Manage and improve CI/CD pipelines
- Automate build, test, and deployment processes
- Define and test rollback strategies
- Perform post-deployment verification and monitoring
- Troubleshoot deployment failures and incidents

#### Goals
- Enable fast, safe, and automated releases
- Reduce deployment risk and mean time to recovery (MTTR)
- Improve deployment frequency and reliability

#### Typical Interactions
- Partners with **Developers** on build/test configuration and release processes
- Coordinates with **PM** for release scheduling and deployment windows
- Works with **Support** for incident handoffs and post-incident analysis

---

### Support / Customer Success Liaison

#### Role Summary
Support and Customer Success Liaisons bring customer-impact context into product decisions, triage production issues, and ensure customer communications and SLAs are met.

#### Responsibilities
- Triage production issues and escalate to engineering teams
- Communicate product updates and changes to customers
- Manage customer SLAs and support response times
- Collect and prioritize customer feedback
- Coordinate post-incident and post-release communications

#### Goals
- Ensure customer satisfaction and trust
- Prioritize fixes for high-impact customer issues
- Provide early signals on product usability and reliability

#### Typical Interactions
- Escalates issues to **PM/Engineering** based on severity and customer impact
- Helps prioritize bug fixes and hot-fixes with **Delivery Lead**
- Coordinates stakeholder communications with **PM** on incidents and releases

---

### Security Officer / Security Reviewer

#### Role Summary
Security Officers and Security Reviewers perform security reviews, approve security exceptions, trigger security incident procedures, and ensure compliance with security policies.

#### Responsibilities
- Review designs and code for security vulnerabilities
- Approve or reject security exceptions and deviations
- Coordinate security incident response when triggered
- Ensure compliance with security and privacy policies
- Provide security guidance and training to teams

#### Goals
- Protect customer data and system integrity
- Reduce security risk and compliance violations
- Enable secure product development at velocity

#### Typical Interactions
- Works with **Developers** and **Engineering Managers** during design and PR reviews
- Partners with **PM** for security risk communications and incident escalation
- Collaborates with **DevOps** on compliance and secure deployment practices

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference specific interaction patterns when assigning ownership or resolving cross-functional questions.

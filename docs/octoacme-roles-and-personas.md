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

## QA / Testing

### Role Summary
QA Engineers define and execute test strategies to ensure that delivered software meets quality, reliability, and acceptance criteria before release. They act as quality advocates throughout the project lifecycle.

### Responsibilities
- Define test plans, test cases, and acceptance test criteria
- Execute manual and automated tests across functional and non-functional areas
- Report, track, and verify bugs and regressions
- Collaborate with Developers and Product Managers on edge cases and coverage gaps
- Participate in release readiness reviews

### Goals
- Prevent defects from reaching production
- Maintain confidence in delivery quality through every sprint
- Provide clear, actionable feedback to development teams

### Typical Communication
- Bug reports and test result summaries
- Sprint reviews and release sign-off meetings
- Coordination with Developers on test environments and automation

### Project Lifecycle Fit
Active from requirements refinement through release; responsible for sign-off at each quality gate before deployment.

---

## Stakeholders

### Role Summary
Stakeholders are internal or external parties with a vested interest in project outcomes. They provide business direction, validate priorities, and hold accountability for results in their domain.

### Responsibilities
- Communicate business goals, constraints, and priorities
- Review and approve key deliverables, roadmap changes, and release decisions
- Escalate issues or risks that affect strategic objectives
- Provide domain knowledge and feedback during discovery and review phases

### Goals
- Ensure the project delivers value aligned with organizational objectives
- Maintain visibility into progress, risks, and decisions
- Support the team with timely approvals and inputs

### Typical Communication
- Roadmap and milestone reviews
- Escalation and decision-making for cross-functional issues
- Stakeholder briefings from Product Managers and Project Managers

### Project Lifecycle Fit
Engaged at key milestones—discovery, planning, major reviews, and release decisions—rather than day-to-day delivery.

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between stakeholder needs and development execution. They translate business requirements into clear, actionable specifications that Product Managers and Developers can act on.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Develop use cases, user stories, and acceptance criteria in collaboration with Product Managers
- Analyze current-state processes and identify gaps or improvement opportunities
- Facilitate requirements reviews and sign-offs with stakeholders
- Support QA by clarifying requirements during test case development

### Goals
- Ensure requirements are complete, unambiguous, and aligned with business goals
- Reduce rework by catching requirement gaps before development begins
- Improve handoff quality between stakeholders and development teams

### Typical Communication
- Requirements workshops with stakeholders and Product Managers
- Written specifications and user story refinement with Developers
- Clarification sessions with QA during test planning

### Project Lifecycle Fit
Most active during discovery, planning, and requirements refinement phases; provides ongoing support during development and QA.

---

## Technical Lead / Architect

### Role Summary
The Technical Lead or Architect guides the technical direction of the project. They make key design decisions, identify technical risks, and ensure the codebase remains maintainable and scalable.

### Responsibilities
- Define and communicate technical architecture and design standards
- Review system design proposals and significant code changes
- Identify and mitigate technical risks and dependencies
- Guide Developers on implementation approaches and trade-offs
- Collaborate with Product Managers on feasibility and effort estimation

### Goals
- Maintain a coherent, sustainable technical architecture
- Reduce technical debt and minimize costly late-stage redesigns
- Enable Developers to work confidently within clear technical boundaries

### Typical Communication
- Architecture decision records and design documents
- Code and design reviews with Developers
- Technical risk discussions with Project Managers and Product Managers

### Project Lifecycle Fit
Engaged from early discovery through delivery; particularly critical during planning, design, and high-complexity development sprints.

---

## Scrum Master / Delivery Facilitator

### Role Summary
The Scrum Master or Delivery Facilitator supports the team's delivery process by facilitating ceremonies, removing blockers, and promoting continuous improvement. They focus on team health and flow rather than on specific features or outcomes.

### Responsibilities
- Facilitate sprint ceremonies: planning, standups, reviews, and retrospectives
- Identify and remove impediments affecting team delivery
- Coach team members on agile practices and self-organization
- Track team velocity and flag systemic delivery risks to Project Managers
- Foster a culture of transparency, accountability, and continuous improvement

### Goals
- Maximize team delivery efficiency and predictability
- Ensure blockers are resolved quickly and transparently
- Support a healthy, collaborative team environment

### Typical Communication
- Daily standups and sprint retrospectives
- Blocker tracking and escalation to Project Managers
- Coordination with Product Managers on backlog readiness

### Project Lifecycle Fit
Present across all sprints and delivery phases; most impactful during team onboarding and process stabilization.

---

## UX / Product Designer

### Role Summary
UX and Product Designers define user experience flows, interface designs, and interaction patterns. They ensure that product decisions are grounded in user needs and result in usable, accessible experiences.

### Responsibilities
- Conduct user research and synthesize insights into design decisions
- Create wireframes, prototypes, and high-fidelity designs for review
- Define interaction patterns and visual standards in collaboration with Developers
- Validate designs through usability testing and stakeholder feedback
- Work with QA to establish acceptance criteria for UX quality

### Goals
- Deliver experiences that are intuitive, accessible, and aligned with user needs
- Reduce development rework by resolving UX ambiguity early
- Maintain design consistency across the product

### Typical Communication
- Design reviews with Product Managers and Developers
- Prototype walkthroughs with stakeholders
- Handoff documentation and design specs for Developers

### Project Lifecycle Fit
Most active during discovery and design phases; remains involved during development for design QA and iteration.

---

## Release Manager

### Role Summary
The Release Manager coordinates the logistics and readiness of software releases. They ensure that deployments are planned, communicated, and executed safely across all affected teams and environments.

### Responsibilities
- Define and maintain the release calendar and deployment plan
- Coordinate release readiness reviews with Development, QA, and Operations
- Manage rollback plans and contingency procedures for high-risk releases
- Communicate release timelines and impacts to stakeholders and Project Managers
- Track post-release stability and coordinate incident response if needed

### Goals
- Ensure releases are predictable, low-risk, and well-communicated
- Minimize production incidents caused by deployment failures
- Maintain clear accountability for go/no-go release decisions

### Typical Communication
- Release readiness checklists and go/no-go meetings with QA and Project Managers
- Deployment notices and stakeholder communications
- Post-release review sessions with Developers and Operations

### Project Lifecycle Fit
Engaged during the later stages of development, QA sign-off, and post-release stabilization.

---

## Support / Operations Representative

### Role Summary
The Support or Operations Representative brings a production and operational perspective into the project team. They advocate for system reliability, supportability, and smooth incident response based on real-world operational experience.

### Responsibilities
- Provide production feedback, incident patterns, and operational risk context during planning and design
- Review proposed changes for operational impact, monitoring, and supportability
- Contribute to on-call runbooks, incident response procedures, and deployment notes
- Participate in release readiness reviews to assess operational risk
- Act as the escalation point for production issues during and after release

### Goals
- Ensure that new features and changes are operable and maintainable in production
- Reduce mean time to resolution for production incidents
- Close the feedback loop between production operations and development

### Typical Communication
- Incident reviews and post-mortems with Developers and Project Managers
- Operational readiness reviews with Release Managers and QA
- Ongoing feedback on monitoring coverage and alerting thresholds

### Project Lifecycle Fit
Engaged during design review, pre-release readiness, and post-release stabilization phases.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.


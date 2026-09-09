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
QA and Testing professionals ensure product quality by designing and executing tests, validating acceptance criteria, and identifying defects before release. They collaborate closely with developers and product managers to maintain quality gates throughout the project lifecycle.

### Responsibilities
- Design and execute test plans covering unit, integration, and end-to-end scenarios
- Validate features against acceptance criteria defined by Product and Project Managers
- Identify, document, and track defects with clear reproduction steps
- Perform regression and smoke testing before releases
- Collaborate with developers on test automation and CI configuration
- Ensure security and performance testing are included in quality gates
- Participate in sprint planning to understand testing scope and dependencies

### Goals
- Maintain high product quality and customer confidence
- Catch issues early to reduce production incidents
- Enable fast, confident releases through automated testing
- Reduce rework and defect escape rates

### Interaction with Other Roles
- **With Developers**: Partner on test automation, CI pipeline improvements, and technical test strategy
- **With Product Managers**: Clarify acceptance criteria and validate that features meet business requirements
- **With Project Managers**: Report quality metrics, escalate blockers, and update risk registers with quality-related issues
- **With Technical Leads**: Collaborate on test architecture and performance benchmarking

### Typical Communication
- Test results and quality metrics in sprint reviews
- Defect logs and blockers in daily standups
- Test plan discussions during planning sessions
- Pre-release quality sign-off and release readiness reports
- Post-release defect analysis and retrospectives

---

## Technical Lead

### Role Summary
Technical Leads provide architectural guidance, mentor developers, and ensure technical quality and scalability across the project. They bridge product requirements and technical implementation, enabling the team to make sound technical decisions.

### Responsibilities
- Mentor team members on technical standards and best practices
- Review and approve high-level technical designs and architecture decisions
- Identify technical risks and propose mitigations in collaboration with Project Managers
- Ensure code quality, testing, and performance standards are met
- Collaborate with Product Managers on technical trade-offs and feasibility assessments
- Lead technical retrospectives and code review discussions
- Support capacity planning and effort estimation for complex technical work
- Champion technical debt reduction and refactoring initiatives

### Goals
- Deliver scalable, maintainable, and secure code
- Reduce technical debt and prevent architecture rework
- Build team capability and knowledge across the project
- Enable faster delivery through sound technical decisions

### Interaction with Other Roles
- **With Developers**: Provide technical guidance, mentor on best practices, and conduct architecture reviews
- **With Product Managers**: Advise on technical feasibility, trade-offs, and effort implications of features
- **With Project Managers**: Escalate technical risks, support timeline estimation, and communicate technical dependencies
- **With QA**: Partner on performance and security testing requirements; define technical acceptance criteria

### Typical Communication
- Design review sessions and technical architecture discussions
- Code review feedback and architecture decision records (ADRs)
- Technical risk escalations and mitigation plans shared in weekly syncs
- Mentoring and knowledge-sharing sessions during standups and retrospectives
- Technical documentation and best practices guides

---

## Business Analyst

### Role Summary
Business Analysts bridge product vision and engineering execution by gathering requirements, documenting workflows, and ensuring user needs are met. They serve as translators between stakeholders and the delivery team, reducing ambiguity and rework.

### Responsibilities
- Gather and document business and user requirements from stakeholders
- Create detailed user stories, workflows, and acceptance criteria
- Validate solutions with stakeholders and end-users through UAT and feedback sessions
- Conduct user research and feedback analysis to inform product decisions
- Support UAT (User Acceptance Testing) planning and execution
- Document business rules, constraints, and edge cases clearly
- Identify dependencies and impact analysis for cross-team features
- Participate in backlog refinement to improve clarity and testability

### Goals
- Ensure features solve real customer problems and deliver measurable value
- Reduce rework and scope creep through clear, unambiguous requirements
- Maintain alignment between business goals and delivered features
- Enable faster development cycles by minimizing requirement clarifications

### Interaction with Other Roles
- **With Product Managers**: Clarify business objectives and priority trade-offs; ensure requirements align with product roadmap
- **With Developers**: Provide detailed specifications and answer clarification questions; validate technical feasibility
- **With Project Managers**: Communicate requirement scope changes and flag dependencies for risk management
- **With QA**: Define test scenarios and acceptance criteria; support test case development

### Typical Communication
- Requirements documentation and user stories in backlog
- Stakeholder feedback synthesis and updates in sprint reviews
- User testing and validation results in retrospectives
- Weekly alignment sessions with Product and Project Managers
- Impact assessments and dependency matrices for cross-team work

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors provide business authority, funding, and escalation paths for strategic projects. They ensure alignment with organizational goals, remove high-level blockers, and serve as the executive voice for project prioritization and resource allocation.

### Responsibilities
- Approve project charter and resource allocation
- Attend kickoff and major milestone reviews to ensure alignment
- Provide strategic guidance and business context for prioritization decisions
- Remove business and organizational blockers that impede progress
- Approve release gates for major features and determine go/no-go decisions
- Participate in executive retrospectives and post-mortems for strategic learning
- Advocate for the project within the organization and secure stakeholder buy-in
- Monitor key metrics and business outcomes aligned to project goals

### Goals
- Ensure projects deliver measurable business value and ROI
- Minimize unplanned disruptions and resource conflicts across the organization
- Enable fast, confident decision-making through clear authority and accountability
- Maximize organizational alignment and stakeholder confidence

### Interaction with Other Roles
- **With Project Managers**: Provide strategic direction and escalation support; review status reports and risk registers
- **With Product Managers**: Align on business objectives and success metrics; approve feature prioritization
- **With Developers**: Communicate business context and strategic importance; attend key reviews
- **With all roles**: Serve as tiebreaker for business trade-offs and strategic decisions

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Escalation for business-blocking issues and dependencies
- Post-release success metrics and retrospectives
- Executive steering committee meetings and board updates
- Ad-hoc strategic decisions via PM escalation channels

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference persona interactions to understand how roles collaborate and escalate during project execution.

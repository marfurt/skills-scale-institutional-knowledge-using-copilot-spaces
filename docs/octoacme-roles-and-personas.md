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

## Design Lead

### Role Summary
The Design Lead owns the UI/UX vision and design system consistency across the project. They ensure that design intent is accurately translated into the delivered product by collaborating closely with Product Managers, Project Managers, and Developers from planning through delivery.

### Responsibilities
- Deliver wireframes, prototypes, and design specifications
- Maintain and evolve design system standards
- Collaborate with PdM during discovery and with Developers during implementation
- Conduct design reviews and provide feedback on PRs that affect UI/UX
- Participate in sprint planning to estimate design effort and unblock developers

### Goals
- User-friendly and visually consistent interfaces
- Efficient design-to-build handoff that minimizes back-and-forth
- Design decisions grounded in user research and product goals

### Typical Communication
- Design critique meetings and async reviews (e.g., Figma comments)
- Attendance at sprint planning and review/demo sessions
- Coordination with Developers via issue comments and PR feedback

### Interactions with Other Roles
- **PdM**: Aligns on user needs and product direction; translates requirements into design solutions.
- **PM**: Communicates design milestones, flags scope changes driven by design discoveries.
- **Developers**: Provides specs and assets; reviews implementations for fidelity to design.

---

## QA Lead

### Role Summary
The QA Lead owns the end-to-end quality assurance strategy for the project, including test planning, test execution, and release readiness verification. They are the gatekeeper for quality before any release is approved.

### Responsibilities
- Author and maintain test plans, test cases, and acceptance test scripts
- Oversee manual and automated testing efforts across the delivery team
- Report test findings, defects, and risk assessments to the PM and team
- Verify that all Acceptance Criteria are met before sign-off on a release
- Drive improvements to testing tooling, processes, and coverage

### Goals
- High product quality with minimal defects reaching production
- Clear, traceable acceptance criteria coverage
- Efficient test cycles that don't block delivery

### Typical Communication
- Test planning sessions at the start of each sprint or feature cycle
- Bug triage and status meetings during QA phases
- Release readiness sign-off communicated to PM and stakeholders

### Interactions with Other Roles
- **PM**: Reports test status, escalates blocking defects, provides release readiness confirmation.
- **PdM**: Clarifies acceptance criteria and validates that test coverage aligns with product intent.
- **Developers**: Collaborates on bug reproduction and resolution; aligns on testability during planning.
- **DevOps Engineer**: Coordinates on CI/CD pipeline test integration and environment readiness.

---

## DevOps Engineer

### Role Summary
The DevOps Engineer is responsible for build automation, deployment pipelines, infrastructure reliability, and operational monitoring. They ensure the team can deliver changes quickly and safely to all environments.

### Responsibilities
- Maintain and improve CI/CD pipelines and deployment automation
- Manage infrastructure as code (IaC) and environment configurations
- Ensure rollback procedures and disaster-recovery plans are documented and tested
- Monitor production systems and respond to infrastructure-level incidents
- Integrate security scanning and compliance checks into the pipeline

### Goals
- Reliable, automated delivery pipeline with minimal manual steps
- Rapid recovery from incidents with documented runbooks
- Minimal unplanned downtime across all environments

### Typical Communication
- Deployment status updates shared with PM and team
- Incident debriefs and post-mortems documented in the project repo
- Async coordination with Developers and QA Lead on environment issues

### Interactions with Other Roles
- **PM**: Communicates deployment schedules, infrastructure risks, and incident status.
- **Developers**: Provides pipeline tooling, reviews infrastructure-affecting code changes, and unblocks environment issues.
- **QA Lead**: Ensures test environments are stable and that test automation is integrated into CI.

---

## Tech Writer

### Role Summary
The Tech Writer creates and maintains user-facing documentation, onboarding guides, internal knowledge-base articles, and process documentation. They reduce knowledge silos and ensure consistent, accurate information is accessible to all team members and stakeholders.

### Responsibilities
- Write and organize user guides, API docs, FAQs, and release notes
- Keep internal onboarding guides and process documentation up to date
- Review PRs and issues for documentation impact; open follow-up docs tasks as needed
- Collaborate with Developers and PdM to ensure technical accuracy of content
- Maintain the `docs/` folder structure and naming conventions

### Goals
- Reduce onboarding time for new team members
- Minimize repeated questions from users or the team through self-service documentation
- Ensure every release is accompanied by clear, accurate release notes

### Typical Communication
- Docs review sessions (sync or async) as part of sprint ceremonies
- Async PR comments to flag or improve documentation
- Coordination with PM for release notes and stakeholder communications

### Interactions with Other Roles
- **PM**: Receives release schedule and context to prepare timely release notes and comms.
- **PdM**: Aligns on product messaging and ensures docs reflect the intended user experience.
- **Developers**: Reviews technical accuracy of guides; developers flag doc tasks in PRs.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.


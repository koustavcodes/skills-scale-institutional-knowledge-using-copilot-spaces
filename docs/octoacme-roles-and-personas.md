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

## QA/Testing Specialist

### Role Summary
QA/Testing Specialists design, execute, and maintain test plans to ensure that features meet acceptance criteria and quality standards before release. They serve as the quality gate between development and production.

### Responsibilities
- Design and maintain test plans, test cases, and automated test suites
- Validate acceptance criteria for each feature and release
- Identify, document, and track defects through resolution
- Coordinate testing handoffs with Developers and Project Managers
- Provide quality signal feedback to Product Managers
- Participate in release readiness reviews and sign-off

### Goals
- Ensure every release meets agreed acceptance criteria and quality standards
- Reduce defect escape rate to production
- Continuously improve test coverage and automation

### Typical Communication
- Testing status updates during sprint reviews and pre-release checkpoints
- Defect reports and QA handoff notes shared with Developers and PM
- Participation in retrospectives to surface recurring quality issues

### Interaction with Existing Roles
- **Developers**: receives code handoffs, collaborates on testability and bug fixes
- **Project Manager**: aligns on testing timelines, escalates blocking defects
- **Product Manager**: provides quality signals and flags acceptance criteria ambiguities

---

## Release Manager

### Role Summary
Release Managers coordinate all release activities, from scheduling and preparation to communication and post-release verification. They ensure deployments are smooth, risks are managed, and stakeholders are informed.

### Responsibilities
- Own and maintain the release schedule and deployment calendar
- Coordinate go/no-go decisions with PM, QA, and engineering leads
- Ensure all pre-release requirements (checklists, sign-offs, release notes) are complete
- Communicate release plans and outcomes to stakeholders and support teams
- Manage rollback decisions and incident coordination during deployments
- Track post-release metrics and capture lessons learned

### Goals
- Deliver releases on schedule with minimal incidents
- Maintain clear communication across all stakeholders throughout the release lifecycle
- Continuously improve the release process based on retrospective feedback

### Typical Communication
- Release schedule and go/no-go announcements to the full team
- Pre-release briefings with QA, Developers, and Project Managers
- Post-release summaries and incident reports shared with stakeholders

### Interaction with Existing Roles
- **Project Manager**: aligns release schedule with project milestones and dependencies
- **Developers**: coordinates deployment windows and rollback procedures
- **QA/Testing Specialist**: confirms QA sign-off before each release
- **Stakeholders**: sends release announcements and status updates

---

## Business Analyst

### Role Summary
Business Analysts gather and refine requirements, bridging gaps between stakeholders and technical teams. They translate business needs into actionable specifications that developers and QA can implement and verify.

### Responsibilities
- Facilitate requirements workshops and stakeholder interviews
- Document functional and non-functional requirements with clear acceptance criteria
- Maintain a requirements traceability matrix linking features to business goals
- Identify and resolve ambiguities or scope gaps before development begins
- Support Project Managers in scope definition and change management
- Review delivered features against original requirements

### Goals
- Ensure requirements are clear, complete, and aligned to business objectives
- Reduce rework caused by misunderstood or incomplete specifications
- Enable teams to deliver features that genuinely meet stakeholder needs

### Typical Communication
- Requirements documents and user story briefs shared with Product and Project Managers
- Facilitation of refinement sessions with Developers before sprint planning
- Change request summaries and impact assessments for scope adjustments

### Interaction with Existing Roles
- **Product Manager**: collaborates on prioritization and translating strategy into requirements
- **Project Manager**: supports scope definition and flags risks from unclear requirements
- **Developers**: provides clarifications and accepts or rejects delivered features
- **QA/Testing Specialist**: ensures acceptance criteria are testable and unambiguous

---

## Technical Writer

### Role Summary
Technical Writers author and maintain documentation including user guides, API references, internal runbooks, and release notes. They ensure that documentation is accurate, accessible, and kept up to date throughout the project lifecycle.

### Responsibilities
- Write and maintain user-facing documentation, API references, and internal runbooks
- Author release notes for each release in collaboration with Developers and Release Manager
- Review and refine documentation based on feedback from QA and end users
- Establish and uphold documentation standards and templates for the team
- Coordinate documentation reviews with subject-matter experts before publishing

### Goals
- Ensure all features and processes are accurately and clearly documented
- Reduce support burden by providing self-service documentation
- Keep documentation synchronized with each product release

### Typical Communication
- Draft release notes and documentation reviews shared with PM and Developer leads
- Documentation status updates during sprint reviews
- Feedback collection from QA and support teams to improve existing content

### Interaction with Existing Roles
- **Developers**: collects technical details, reviews drafts for accuracy
- **Product Manager**: aligns documentation scope with product direction
- **Release Manager**: coordinates release notes delivery before each release
- **QA/Testing Specialist**: receives feedback on documentation gaps found during testing

---

## Stakeholder/Advisor

### Role Summary
Stakeholders and Advisors provide subject-matter expertise, strategic guidance, and decision-making authority for the project. They represent business, customer, or domain interests and ensure the project delivers value to the broader organization.

### Responsibilities
- Provide subject-matter expertise and domain guidance throughout the project
- Attend major project reviews, demos, and go/no-go checkpoints
- Guide prioritization decisions and trade-off discussions
- Escalate issues that impact business commitments or organizational strategy
- Communicate expectations and constraints to the delivery team
- Approve key deliverables and project milestones where required

### Goals
- Ensure the project delivers measurable business value
- Maintain alignment between project outcomes and organizational objectives
- Enable timely, informed decision-making to unblock delivery

### Typical Communication
- Monthly stakeholder updates from the Project Manager
- Participation in sprint reviews and milestone demos
- Escalation channels for business-critical issues

### Interaction with Existing Roles
- **Project Manager**: receives status updates, provides guidance on priorities and escalations
- **Product Manager**: aligns on product direction and business outcomes
- **Business Analyst**: shares domain knowledge and validates requirements
- **Release Manager**: approves major release milestones and business communications

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [OctoAcme Project Management Overview](octoacme-project-management-overview.md) for how all roles fit together in the project lifecycle.


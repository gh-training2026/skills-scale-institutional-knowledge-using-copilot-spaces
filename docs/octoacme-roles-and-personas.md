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

## Technical Lead

### Role Summary
Technical Leads provide architectural guidance, set technical standards, and mentor engineering team members. They ensure technical decisions align with product goals and long-term maintainability.

### Responsibilities
- Lead design reviews and architectural decisions
- Advise on best practices, tooling, and technical standards
- Identify and help resolve complex technical blockers
- Interface with stakeholders for technical alignment
- Support prioritization of technical debt
- Mentor developers and facilitate knowledge sharing

### Goals
- Maintain architectural integrity and code quality
- Reduce technical risk across deliverables
- Enable developers to work effectively within agreed standards

### Typical Communication
- Architecture decision records (ADRs) and design docs
- Technical reviews in PRs and design sessions
- Escalation paths with Project Manager and Product Manager for technical risk

### Interactions with Other Roles
- **Developers:** Provides mentorship, reviews designs, unblocks complex issues
- **Product Manager:** Aligns technical trade-offs with product goals
- **Project Manager:** Surfaces technical risks and dependencies early
- **QA Lead:** Collaborates on defect triage and early quality checks
- **Stakeholder:** Communicates technical constraints and progress at an appropriate level

---

## UX Designer

### Role Summary
UX Designers ensure user-centric approaches across product design. They own wireframes, prototypes, and usability feedback to drive intuitive product experiences.

### Responsibilities
- Conduct user research and usability testing
- Produce mockups, wireframes, and design specs
- Review designs with stakeholders and iterate based on feedback
- Maintain a design system aligned with product standards
- Communicate design decisions and rationale to the team

### Goals
- Deliver clear, user-validated designs on schedule
- Reduce rework through early design feedback loops
- Ensure accessibility and usability across all features

### Typical Communication
- Design critiques and review sessions
- Shared design files (e.g., Figma) with annotated specs
- Collaboration in sprint planning and backlog refinement

### Interactions with Other Roles
- **Product Manager:** Aligns user research with product vision and priorities
- **Developers:** Provides design specs and answers implementation questions
- **QA Lead:** Collaborates to validate design acceptance criteria
- **Stakeholder:** Shares prototypes and collects feedback during milestone reviews
- **Technical Lead:** Validates design feasibility within technical constraints

---

## QA Lead

### Role Summary
QA Leads own the end-to-end test strategy, quality reporting, and defect triage. They ensure releases meet quality standards and coordinate go/no-go decisions.

### Responsibilities
- Define test plans and oversee test execution across sprints
- Coordinate with Developers and Technical Lead for early defect detection
- Monitor release readiness and lead go/no-go quality decisions
- Maintain and improve testing frameworks and tooling
- Report on quality metrics, risk areas, and outstanding defects

### Goals
- Achieve and maintain high release quality standards
- Minimize escaped defects and production incidents
- Establish repeatable, efficient testing processes

### Typical Communication
- Test plans, defect reports, and quality dashboards
- Sprint review input on acceptance criteria completion
- Escalation of high-priority blockers to Project Manager

### Interactions with Other Roles
- **Developers:** Collaborates on defect fixes, test coverage, and early testing
- **Technical Lead:** Coordinates on architectural testing and root cause analysis
- **Project Manager:** Provides quality gates status and flags release blockers
- **Product Manager:** Validates acceptance criteria are met before release
- **UX Designer:** Validates that implemented designs match design specs
- **Stakeholder:** Reports release readiness at milestone reviews

---

## Stakeholder (Business/External Partner)

### Role Summary
Stakeholders provide subject-matter expertise, business context, and approvals for functional milestones. They represent external or business interests and validate that deliverables meet their needs.

### Responsibilities
- Supply requirements, expectations, and timelines at project initiation
- Review milestone demos and provide timely feedback
- Sign off on releases and functional milestones
- Escalate business-side risks or priority changes to Project Manager or Product Manager
- Participate in go/no-go decisions when relevant

### Goals
- Ensure delivered solutions meet business objectives
- Provide clear, actionable feedback to reduce rework
- Maintain visibility into project progress and risk

### Typical Communication
- Monthly stakeholder updates and milestone demos
- Formal sign-off communications at release gates
- Ad-hoc check-ins for high-priority escalations

### Interactions with Other Roles
- **Project Manager:** Regular alignment on schedule, scope, and risks
- **Product Manager:** Collaborates on requirements and priorities
- **Technical Lead:** Receives high-level technical updates as needed
- **QA Lead:** Reviews release readiness evidence before sign-off

---

## Cross-Role Communication Pathways

The table below summarizes key hand-off points and communication touchpoints between roles:

| From | To | When | Channel |
|------|----|------|---------|
| Product Manager | Technical Lead | New feature scoping | Design meeting / spec doc |
| Technical Lead | Developers | Architecture decisions | ADR / design doc |
| UX Designer | Developers | Feature design ready | Design file + spec handoff |
| Developers | QA Lead | Feature ready for testing | PR / ticket status update |
| QA Lead | Project Manager | Release blockers / quality gates | Status report / standup |
| Project Manager | Stakeholder | Milestone updates | Status email / demo session |
| Stakeholder | Product Manager | Requirement changes or priorities | Meeting / written feedback |
| QA Lead | Product Manager | Acceptance criteria validation | Sprint review |
| Technical Lead | QA Lead | Architectural risks | Design review / escalation |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to `octoacme-onboarding-checklist.md` for role-specific onboarding steps.
- Refer to `octoacme-handoff-template.md` for structured hand-off processes between roles.


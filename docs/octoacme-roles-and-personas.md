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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality strategy, test planning, and quality assurance for the project. They ensure that deliverables meet acceptance criteria and quality standards before release.

### Responsibilities
- Define testing strategy and test plan aligned with project scope
- Collaborate with developers and product managers on acceptance criteria clarity
- Design and execute manual and automated test cases
- Identify and triage quality issues (bugs, performance, usability)
- Validate that exit criteria are met before release

### Goals
- Catch defects early and prevent production issues
- Ensure user-visible quality and reliability
- Reduce rework and post-release support burden

### Typical Communication
- Weekly QA status in execution sync
- Test result summaries in sprint reviews
- Defect reports in issue tracking system
- Collaboration with developers on test automation

### Interaction with Other Roles
- Works closely with **Developers** to clarify acceptance criteria and design test automation
- Partners with **Product Managers** to validate feature completeness and user scenarios
- Supports **Project Managers** with quality metrics and release readiness assessments
- Collaborates with **Technical Leads** on test infrastructure and automation strategy

---

## Technical Lead / Architect

### Role Summary
Technical Leads define the technical vision and direction for the project. They ensure architectural decisions are sound, manage technical debt, and mentor the engineering team.

### Responsibilities
- Design system architecture and major technical decisions
- Review technical designs and code for alignment with standards
- Identify and manage technical risks and dependencies
- Mentor developers and guide technical problem-solving
- Plan for scalability, performance, and maintainability

### Goals
- Deliver technically sound, maintainable solutions
- Reduce rework and technical debt accumulation
- Build team technical capability

### Typical Communication
- Technical design reviews and architecture discussions
- Code review guidance and mentoring
- Risk identification in planning and execution syncs
- Technical documentation and decision records

### Interaction with Other Roles
- Mentors and guides **Developers** on technical decisions and best practices
- Partners with **Product Managers** on technical feasibility and trade-offs
- Advises **Project Managers** on technical risks and dependencies
- Works with **QA/Testing Leads** on test automation architecture and infrastructure
- Supports **DevOps/Infrastructure Engineers** on deployment and scalability concerns

---

## Executive Sponsor / Stakeholder

### Role Summary
Executive Sponsors provide business context, strategic alignment, and organizational support for projects. They approve scope changes, remove business blockers, and ensure alignment with organizational priorities.

### Responsibilities
- Approve project initiation, scope, and budget
- Provide strategic business context and priorities
- Remove organizational and business blockers
- Approve major scope changes or go/no-go decisions
- Communicate project status to leadership and board (as needed)

### Goals
- Ensure project delivers business value and ROI
- Maintain organizational alignment
- Enable team success by removing constraints

### Typical Communication
- Monthly or milestone-based executive updates
- Go/no-go decision reviews
- Escalation path for business-blocking issues
- Stakeholder briefings and announcements

### Interaction with Other Roles
- Provides business context and prioritization to **Product Managers**
- Removes organizational blockers for **Project Managers**
- Approves major scope or timeline changes affecting the team
- Participates in critical escalations from all team members

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove team impediments, and coach the team on agile practices. They enable continuous improvement and help the team operate efficiently within their chosen agile framework.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Remove team impediments and blockers
- Coach team members on agile practices and mindset
- Track team velocity and sprint metrics
- Help the team identify and implement process improvements

### Goals
- Enable self-organizing, high-performing teams
- Reduce cycle time and improve delivery predictability
- Foster a culture of continuous improvement and psychological safety

### Typical Communication
- Daily standups and ceremony facilitation
- Impediment tracking and escalation
- Sprint metrics and retrospective action items
- Coaching and one-on-one guidance with team members

### Interaction with Other Roles
- Removes blockers identified by **Developers**, **QA/Testing Leads**, and other team members
- Partners with **Project Managers** on planning and metrics
- Coaches all team members on agile best practices
- Helps escalate organizational impediments to **Product Managers** and **Project Managers**

---

## UX/Design Lead

### Role Summary
UX/Design Leads own the user experience strategy, design systems, and usability standards for the project. They ensure solutions are user-centered, accessible, and consistent across touchpoints.

### Responsibilities
- Define UX strategy and design system aligned with product goals
- Create wireframes, prototypes, and design specifications
- Conduct user research and usability testing
- Ensure accessibility standards (WCAG, etc.) are met
- Review implementations for design fidelity and user experience

### Goals
- Deliver user-centered, intuitive solutions
- Maintain design consistency and brand alignment
- Reduce user friction and improve adoption

### Typical Communication
- Design reviews and feedback sessions
- User research findings and recommendations
- Design system documentation
- Collaboration with developers on implementation details

### Interaction with Other Roles
- Partners with **Product Managers** on user scenarios and feature prioritization
- Collaborates with **Developers** on design implementation and accessibility
- Works with **QA/Testing Leads** on usability test planning
- Advises **Technical Leads** on scalable design system architecture

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps/Infrastructure Engineers manage deployment pipelines, infrastructure, monitoring, and reliability. They enable teams to deploy safely and observe system health in production.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Provision and manage infrastructure (cloud, on-premises, hybrid)
- Implement monitoring, logging, and alerting systems
- Plan for scalability, high availability, and disaster recovery
- Support incident response and post-incident analysis

### Goals
- Enable rapid, safe deployments with minimal manual effort
- Maintain high system reliability and performance
- Reduce mean time to recovery (MTTR) for incidents

### Typical Communication
- Deployment and release coordination with the team
- Infrastructure and reliability metrics in status reports
- Incident notifications and post-incident reviews
- Documentation of runbooks and deployment procedures

### Interaction with Other Roles
- Works with **Developers** on deployment procedures and CI/CD improvements
- Supports **Project Managers** on release planning and rollout strategies
- Partners with **Technical Leads** on infrastructure architecture and scalability
- Collaborates with **QA/Testing Leads** on deployment validation and smoke testing
- Advises on production readiness during **Release and Deployment** processes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference persona interaction sections to understand cross-functional dependencies and communication patterns.

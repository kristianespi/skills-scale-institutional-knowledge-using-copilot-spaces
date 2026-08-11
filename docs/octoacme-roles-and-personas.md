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

## Quality Assurance / QA Lead

### Role Summary
QA Leads ensure quality standards are met and features meet acceptance criteria before release. They own the testing strategy, validate user experience, and provide confidence signals for deployment readiness.

### Responsibilities
- Develop and maintain test plans and QA approach for projects
- Define acceptance criteria verification processes
- Execute manual testing and coordinate automated testing
- Validate features meet Definition of Done before marking complete
- Identify and document quality gaps and defects
- Participate in pre-release smoke testing and post-deploy verification

### Goals
- Ensure customer satisfaction through high-quality features
- Reduce production incidents and post-release defects
- Provide clear go/no-go signals for release readiness

### Typical Communication
- QA approach discussions during project planning
- Test plan reviews and status updates in execution guide
- Defect reports and acceptance validation in pull requests
- Pre-release readiness assessments

### Interactions with Existing Roles
- Works with **Developers** to define testability requirements and validate implementation
- Collaborates with **Product Managers** to clarify acceptance criteria and success metrics
- Reports quality signals to **Project Managers** for release planning decisions
- Coordinates with **Release Manager** on pre-release verification procedures

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide technical direction, design guidance, and risk mitigation. They ensure solutions are scalable, maintainable, and aligned with system architecture and technical standards.

### Responsibilities
- Lead technical design discussions and architecture decisions
- Review designs for scalability, performance, and maintainability
- Identify and escalate technical risks and dependencies
- Mentor developers and guide implementation approach
- Ensure code quality standards and best practices
- Coordinate with other technical leads on integration points

### Goals
- Deliver technically sound, scalable solutions
- Reduce technical debt and rework
- Enable team learning and capability growth

### Typical Communication
- Technical design reviews and architecture discussions
- Code review guidance and mentoring
- Risk escalation and dependency coordination
- Technical documentation and Architecture Decision Records (ADRs)

### Interactions with Existing Roles
- Guides **Developers** on design patterns, architecture, and technical best practices
- Partners with **Product Managers** to understand technical feasibility and trade-offs
- Alerts **Project Managers** to technical risks and dependencies affecting timeline
- Advises **Security Lead** on architectural security implications

---

## Scrum Master / Iteration Facilitator

### Role Summary
Scrum Masters facilitate agile ceremonies, remove blockers, and ensure the team adheres to established processes. They enable continuous improvement and help teams maintain sustainable delivery pace.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Identify and escalate blockers preventing team progress
- Coach team members on agile practices and ceremonies
- Track iteration metrics and team velocity
- Foster psychological safety and continuous improvement culture
- Protect team from external interruptions and scope creep

### Goals
- Enable consistent, sustainable team delivery
- Reduce process friction and decision-making overhead
- Build team cohesion and psychological safety
- Improve team efficiency and predictability

### Typical Communication
- Daily standup facilitation and blocker tracking
- Retrospective facilitation and action item tracking
- Iteration metrics and velocity reporting
- One-on-one coaching and feedback

### Interactions with Existing Roles
- Supports **Developers** in maintaining focus and removing impediments
- Coordinates with **Product Managers** on backlog readiness and scope changes
- Works with **Project Managers** on schedule planning and risk escalation
- Ensures all roles have psychological safety to voice concerns and suggestions

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, strategic alignment, and approvals. They ensure project decisions support organizational priorities and have necessary resources and support.

### Responsibilities
- Define business objectives and success criteria
- Provide strategic context and organizational priorities
- Review and approve major project decisions and scope changes
- Allocate resources and resolve organizational blockers
- Provide feedback on progress and business impact
- Communicate project status and outcomes to executive leadership

### Goals
- Ensure projects deliver business value and align with strategy
- Reduce organizational friction and enable team success
- Maintain transparency with leadership and other stakeholders
- Make timely, informed decisions on prioritization and trade-offs

### Typical Communication
- Kickoff and stakeholder alignment meetings
- Monthly status updates and milestone reviews
- Decision approval on scope, timeline, and resource changes
- Executive briefings and outcome reporting

### Interactions with Existing Roles
- Provides direction to **Product Managers** on business priorities and trade-offs
- Reviews timelines and scope with **Project Managers**
- Approves major decisions affecting **Developers**, **QA Leads**, and technical teams
- Escalates organizational blockers for **Project Managers** to resolve

---

## Release Manager

### Role Summary
Release Managers coordinate the deployment process, manage release schedules, and ensure smooth transitions to production. They own release planning, coordination, and post-release verification.

### Responsibilities
- Create and maintain release schedules and deployment windows
- Coordinate pre-release readiness checks and sign-offs from all teams
- Execute or orchestrate deployment procedures
- Prepare and communicate release notes to stakeholders and support
- Coordinate rollback procedures if issues arise
- Run post-deploy verification and monitoring
- Document deployment results and lessons learned

### Goals
- Minimize deployment risk and production incidents
- Ensure predictable, reliable release processes
- Maintain clear communication with all stakeholder groups
- Enable rapid, safe deployment frequency

### Typical Communication
- Release coordination meetings and deployment checklists
- Release notes and stakeholder announcements
- Post-deployment verification reports
- Incident communication during deployment issues
- Rollback coordination and status updates

### Interactions with Existing Roles
- Coordinates with **Developers** on deployment procedures and rollback plans
- Works with **QA Leads** to verify pre-release smoke tests and go/no-go decisions
- Reports deployment status to **Project Managers** and **Stakeholders**
- Collaborates with **Security Lead** on security verification before release
- Communicates with **Technical Leads** on technical deployment considerations

---

## Security Lead

### Role Summary
Security Leads ensure security requirements are met, vulnerabilities are addressed, and the team follows security best practices. They own security scanning, incident response, and compliance considerations.

### Responsibilities
- Define security requirements and acceptance criteria for features
- Coordinate security scanning and vulnerability management in CI
- Review security implications of design and implementation decisions
- Lead security incident response when needed
- Maintain security incident runbooks and escalation paths
- Advise on compliance and regulatory requirements
- Conduct security reviews before major releases

### Goals
- Prevent security vulnerabilities from reaching production
- Enable fast, confident response to security incidents
- Build security awareness and best practices across the team
- Maintain compliance with regulatory and organizational standards

### Typical Communication
- Security requirement discussions during planning
- Security review findings and remediation tracking
- Incident triage and response coordination
- Security scanning results and vulnerability reports
- Training and awareness communications

### Interactions with Existing Roles
- Partners with **Developers** on secure coding practices and vulnerability remediation
- Advises **Product Managers** on security features and compliance requirements
- Reports security risks to **Project Managers** for escalation if needed
- Collaborates with **Technical Leads** on architectural security decisions
- Conducts pre-release reviews with **Release Manager**
- Coordinates with **Stakeholders** on compliance and regulatory matters

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction patterns to understand how roles collaborate across the project lifecycle.

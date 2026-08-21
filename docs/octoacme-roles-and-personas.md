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
QA/Testing Leads define and execute quality strategies, validate acceptance criteria, and ensure products meet quality standards before release. They own testing approaches, test planning, and quality metrics.

### Responsibilities
- Create and maintain test plans and QA strategies aligned with project scope
- Define and document test cases based on acceptance criteria
- Execute manual and automated testing during development and pre-release
- Identify and track defects with clear severity and reproduction steps
- Validate that all acceptance criteria are met before promotion to production
- Mentor developers on testing best practices and quality standards
- Report test coverage metrics and quality insights to the team

### Goals
- Catch defects early and reduce production incidents
- Maintain high product quality and user satisfaction
- Enable fast, confident releases

### Typical Communication
- Test planning meetings and acceptance criteria reviews
- Defect reports and quality status in standups
- Quality metrics and risk reports to PM and Project Manager

### Interaction with Other Roles
- **With Developers**: Collaborates on test case design and provides feedback on code quality and test coverage
- **With Product Managers**: Validates that features meet acceptance criteria and user needs
- **With Project Managers**: Reports quality metrics and identifies risks that impact release timelines

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, approval authority, and strategic direction. They ensure projects align with organizational goals and have necessary resources and executive support.

### Responsibilities
- Define business objectives and success criteria
- Approve project charter and significant scope changes
- Provide resources and resolve escalated blockers
- Review progress at milestone gates and make go/no-go decisions
- Communicate project status to their organization
- Ensure alignment with organizational strategy and priorities

### Goals
- Maximize business value and ROI of project investments
- Ensure clear strategic alignment
- Remove organizational barriers to project success

### Typical Communication
- Project kickoff and planning reviews
- Milestone and gate reviews
- Executive status reports and announcements
- Escalation path for critical blockers

### Interaction with Other Roles
- **With Project Managers**: Provides strategic direction, approvals, and resource allocation
- **With Product Managers**: Aligns business objectives and validates prioritization decisions
- **With All Roles**: Serves as escalation point for critical blockers and business-impacting decisions

---

## Technical Lead/Architect

### Role Summary
Technical Leads define the technical strategy, architecture, and design approach. They ensure solutions are scalable, maintainable, and aligned with system standards.

### Responsibilities
- Define technical architecture and design patterns for projects
- Review technical approaches and code design
- Identify technical risks and propose mitigations
- Ensure code quality standards and best practices are followed
- Guide junior developers and mentor technical growth
- Coordinate with other technical teams on dependencies and integration points

### Goals
- Deliver scalable, maintainable, and reliable systems
- Reduce technical debt and security vulnerabilities
- Enable team efficiency through solid design and standards

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback and mentoring
- Risk identification and mitigation planning
- Cross-team technical coordination

### Interaction with Other Roles
- **With Developers**: Provides technical direction, mentors on best practices, and reviews technical decisions
- **With Project Managers**: Identifies technical risks and informs timeline estimates
- **With QA/Testing Leads**: Defines testability requirements and architecture for quality assurance

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove process impediments, and coach teams on agile practices. They ensure the team follows agreed-upon processes and continuously improves.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove blockers and impediments reported by the team
- Protect the team from external distractions during sprints
- Coach team members on agile practices and continuous improvement
- Track sprint metrics (velocity, burndown, cycle time)
- Identify process improvements and drive adoption

### Goals
- Maintain predictable, sustainable team velocity
- Continuously improve team processes and effectiveness
- Foster psychological safety and team engagement

### Typical Communication
- Facilitation of all agile ceremonies
- Impediment tracking and resolution
- Process improvement proposals in retrospectives
- Metrics reviews with PM and Project Manager

### Interaction with Other Roles
- **With Project Managers**: Supports planning and retrospectives to drive continuous improvement
- **With All Delivery Team Members**: Facilitates ceremonies and removes impediments to productivity
- **With Product Managers**: Ensures clarity on priorities and manages backlog refinement

---

## DevOps/Release Engineer

### Role Summary
DevOps and Release Engineers own the deployment pipeline, infrastructure, and release processes. They enable fast, reliable, and observable deployments.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage infrastructure, environments, and configuration management
- Coordinate and execute production releases
- Monitor production systems for errors, latency, and availability
- Implement security scanning and compliance checks in the pipeline
- Create runbooks and incident response procedures
- Support rollback and incident recovery

### Goals
- Enable fast, safe deployments with high confidence
- Maintain high availability and performance in production
- Reduce mean-time-to-recovery (MTTR) for incidents

### Typical Communication
- Release planning and deployment window coordination
- Post-deploy verification and monitoring
- Incident response and root cause analysis
- Infrastructure and pipeline improvement proposals

### Interaction with Other Roles
- **With Developers**: Supports local development environments and provides deployment guidance
- **With Project Managers**: Coordinates release timelines and communicates deployment readiness
- **With QA/Testing Leads**: Provides testing environments and coordinates smoke test execution
- **With All Roles**: Ensures production observability and incident communication

---

## Designer/UX Lead

### Role Summary
Designers and UX Leads define user experience, visual design, and usability standards. They ensure products are intuitive, accessible, and meet user needs.

### Responsibilities
- Conduct user research and define user personas/journeys
- Create wireframes, prototypes, and design specifications
- Define design systems and component libraries
- Collaborate with developers on design implementation and accessibility
- Conduct usability testing and gather user feedback
- Ensure consistency and accessibility across all user touchpoints
- Mentor developers on design standards and user-centered thinking

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce friction and improve user satisfaction
- Establish scalable design systems and standards

### Typical Communication
- Design reviews and critique sessions
- User research and testing findings
- Design specifications and component documentation
- Collaboration with Product Manager on feature prioritization and acceptance criteria

### Interaction with Other Roles
- **With Product Managers**: Translates user needs into design and accepts feedback on priorities
- **With Developers**: Provides design specifications and collaborates on implementation feasibility
- **With QA/Testing Leads**: Defines accessibility and usability acceptance criteria
- **With All Roles**: Ensures user-centered thinking throughout project delivery

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
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
QA/Testing Leads define testing strategies, coordinate quality assurance activities, and ensure features meet acceptance criteria before release. They partner with developers and product managers to validate that solutions work as intended and meet quality standards.

### Responsibilities
- Design test plans and acceptance criteria validation approaches
- Coordinate manual and automated testing efforts
- Report quality metrics and test coverage
- Participate in release readiness reviews
- Identify and triage defects
- Mentor developers on testability practices

### Goals
- Ensure high-quality releases with minimal defects
- Reduce time spent on post-release troubleshooting
- Maintain team confidence in quality gates

### Interaction with Existing Roles
- **With Developers**: Collaborate on test design, review PRs for testability, and mentor on testing best practices
- **With Product Managers**: Validate acceptance criteria and ensure quality aligns with product expectations
- **With Project Managers**: Provide quality status updates and support release readiness assessments

### Typical Communication
- Sprint planning and backlog refinement
- Quality status in weekly syncs
- Test plan reviews and defect reports
- Release readiness sign-offs

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide architectural guidance, make technology decisions, and ensure the codebase remains maintainable and scalable. They mentor developers and advocate for technical excellence while balancing business timelines.

### Responsibilities
- Design technical architecture and system interactions
- Review complex designs and PRs for architectural alignment
- Identify and mitigate technical risks
- Mentor developers on best practices
- Make trade-off decisions between velocity and technical debt
- Coordinate with DevOps on deployment and infrastructure concerns

### Goals
- Deliver scalable, maintainable solutions
- Reduce technical debt and rework
- Build team technical capability

### Interaction with Existing Roles
- **With Developers**: Provide architectural guidance, review designs, and mentor on technical standards and practices
- **With Project Managers**: Flag technical risks and dependencies; advise on feasibility and timeline impacts
- **With QA/Testing Lead**: Ensure architectural decisions support testability and quality goals

### Typical Communication
- Technical design reviews
- Architecture discussions in planning
- Code review feedback
- Risk escalation for technical blockers

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders or Sponsors provide business context, budget authority, and strategic alignment. They define success from a business perspective and escalate blockers that impede delivery.

### Responsibilities
- Articulate business objectives and success criteria
- Approve scope and timeline trade-offs
- Allocate resources and remove organizational blockers
- Receive and act on escalations
- Communicate project status to broader organization

### Goals
- Ensure project aligns with business strategy
- Maximize ROI on project investment
- Remove barriers to team delivery

### Interaction with Existing Roles
- **With Project Managers**: Receive regular status updates, make strategic decisions, and remove escalated blockers
- **With Product Managers**: Align on business priorities and provide context on organizational constraints
- **With All Roles**: Set expectations, approve major decisions, and communicate outcomes to the organization

### Typical Communication
- Monthly status updates
- Milestone reviews and approvals
- Escalation handling
- Budget and resource reviews

---

## DevOps/Release Engineer

### Role Summary
DevOps and Release Engineers own the deployment pipeline, infrastructure, and release processes. They ensure code can be safely and reliably moved from development to production.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure and environments
- Execute and automate deployments
- Monitor production health and performance
- Coordinate rollback procedures and incident response
- Ensure compliance and security in the deployment process

### Goals
- Enable fast, safe releases with minimal manual work
- Maintain production stability and observability
- Reduce deployment risk and mean time to recovery

### Interaction with Existing Roles
- **With Developers**: Support CI/CD setup, provide deployment documentation, and assist with infrastructure troubleshooting
- **With Project Managers**: Coordinate release timelines, communicate deployment status, and report on infrastructure readiness
- **With Technical Lead/Architect**: Align infrastructure decisions with architectural requirements and scalability goals
- **With QA/Testing Lead**: Enable automated testing in the pipeline and ensure test environments match production

### Typical Communication
- Release planning and pre-deployment reviews
- Incident response coordination
- Infrastructure requirements in planning
- Post-deployment monitoring and validation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

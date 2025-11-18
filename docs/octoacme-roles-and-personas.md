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

## QA Engineers

### Role Summary
QA Engineers ensure product quality through systematic testing, validation, and collaboration with developers. They verify that features meet acceptance criteria and quality standards before release.

### Responsibilities
- Create and execute test plans for features and releases
- Write and maintain automated tests (unit, integration, end-to-end)
- Validate acceptance criteria and report defects
- Collaborate with developers on testability and bug fixes
- Participate in planning to ensure quality requirements are understood

### Goals
- Prevent defects from reaching production
- Maintain high test coverage and reliability
- Reduce time to detect and resolve issues

### Typical Communication
- Test plans and status updates in project boards
- Bug reports and verification notes
- Sprint planning and retrospectives
- Collaboration with developers on test automation

### Interactions with Other Roles
- **Developers:** Collaborate on test automation, provide feedback on defects, and review code for testability
- **Product Managers:** Validate that acceptance criteria are clear and testable, provide feedback on usability
- **Project Managers:** Report testing progress, raise blockers, and coordinate test environment needs
- **DevOps Engineers:** Coordinate test environment setup and CI/CD pipeline integration
- **Support Engineers:** Collaborate on reproducing customer-reported issues and validating fixes

---

## DevOps Engineers

### Role Summary
DevOps Engineers ensure reliable, automated delivery through CI/CD pipelines, infrastructure management, monitoring, and deployment processes. They enable teams to ship quickly and safely.

### Responsibilities
- Build and maintain CI/CD pipelines for automated builds, tests, and deployments
- Manage infrastructure, cloud resources, and environment configurations
- Implement monitoring, logging, and alerting solutions
- Respond to operational issues and maintain system reliability
- Automate repetitive tasks and improve deployment processes
- Ensure security best practices in infrastructure and deployment

### Goals
- Minimize deployment friction and manual processes
- Maintain high system availability and performance
- Enable rapid feedback through automation and monitoring

### Typical Communication
- Infrastructure changes and deployment schedules
- Incident response and postmortem reports
- Pipeline updates and automation improvements
- Capacity planning and performance metrics

### Interactions with Other Roles
- **Developers:** Collaborate on build/test pipelines, provide deployment support, and troubleshoot environment issues
- **Project Managers:** Communicate release readiness, infrastructure constraints, and deployment schedules
- **Product Managers:** Ensure infrastructure supports product requirements and performance goals
- **QA Engineers:** Provide test environments and coordinate automated testing in CI/CD
- **Support Engineers:** Collaborate on incident response, log analysis, and production troubleshooting

---

## UX Designers

### Role Summary
UX Designers advocate for user experience, create intuitive interfaces, and ensure products meet usability standards. They conduct research, create designs, and iterate based on feedback.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and high-fidelity designs
- Define interaction patterns and information architecture
- Collaborate with developers on implementation and feasibility
- Validate delivered features against design specifications
- Maintain design systems and style guides

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support tickets
- Ensure consistency across product features

### Typical Communication
- Design specifications and prototypes
- User research findings and recommendations
- Usability test results and feedback
- Design review sessions with team

### Interactions with Other Roles
- **Product Managers:** Partner on requirements gathering, validate solutions meet user needs, and prioritize design debt
- **Developers:** Collaborate on implementation feasibility, review UI components, and clarify design specifications
- **QA Engineers:** Define usability test cases and validate user experience in delivered features
- **Business Analysts:** Incorporate process flows and user journeys into design work
- **Support Engineers:** Analyze user feedback and support tickets to identify UX improvements

---

## Business Analysts

### Role Summary
Business Analysts bridge business needs and technical solutions by eliciting requirements, documenting processes, and validating that delivered solutions meet business objectives.

### Responsibilities
- Elicit and document business requirements from stakeholders
- Create process flows, use cases, and functional specifications
- Facilitate backlog refinement and requirements workshops
- Validate solutions against business needs and success criteria
- Support change management and user documentation
- Analyze data to support decision-making and prioritization

### Goals
- Ensure solutions address actual business problems
- Reduce requirement ambiguity and rework
- Enable stakeholder alignment on scope and priorities

### Typical Communication
- Requirements documents and user stories
- Process flow diagrams and data models
- Workshop facilitation and stakeholder meetings
- Analysis reports and recommendations

### Interactions with Other Roles
- **Product Managers:** Partner on roadmap planning, validate business value, and refine user stories
- **Project Managers:** Support scope definition, facilitate requirements workshops, and track requirement changes
- **Developers:** Clarify requirements, answer questions during implementation, and validate solutions
- **Stakeholders:** Act as liaison, gather requirements, and communicate solution capabilities
- **UX Designers:** Collaborate on user research and ensure designs meet business requirements

---

## Support Engineers

### Role Summary
Support Engineers handle post-release issues, analyze user-reported problems, and maintain support knowledge bases. They provide critical feedback for product improvements and ensure customer success.

### Responsibilities
- Triage and resolve customer-reported issues
- Document common problems and solutions in knowledge base
- Escalate bugs and feature requests to appropriate teams
- Analyze support trends and provide product feedback
- Collaborate on incident response for production issues
- Create and maintain customer-facing documentation

### Goals
- Minimize customer impact from issues
- Reduce resolution time through documentation and automation
- Provide actionable feedback to improve product quality

### Typical Communication
- Support tickets and issue escalations
- Knowledge base articles and FAQs
- Trend reports and feedback summaries
- Incident response coordination

### Interactions with Other Roles
- **Developers:** Triage and escalate bugs, provide reproduction steps, and verify fixes
- **QA Engineers:** Collaborate on reproducing customer issues and validating fixes before release
- **Product Managers:** Report usage trends, feature requests, and customer pain points
- **Project Managers:** Escalate critical issues, coordinate emergency fixes, and provide release feedback
- **DevOps Engineers:** Collaborate on production troubleshooting, log analysis, and incident response
- **UX Designers:** Share user feedback and usability issues to inform design improvements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.


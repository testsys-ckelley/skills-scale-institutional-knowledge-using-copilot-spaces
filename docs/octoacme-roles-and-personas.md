# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

PM refers to Project Manager; PdM refers to Product Manager.

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

## Release Manager

### Role Summary
Release Managers coordinate release readiness, deployment timing, and go/no-go communication so teams can deliver changes safely.

### Responsibilities
- Maintain the release checklist, deployment window, and release notes
- Gather readiness evidence from developers and QA/testing, including passing CI, security scans, and smoke tests
- Confirm rollback plans and post-deployment verification with Support / Operations
- Coordinate release dependencies with the PM and scope expectations with the PdM

### Goals
- Reduce failed deployments and last-minute release surprises
- Make release readiness and handoffs clear to stakeholders

### Typical Communication
- Readiness reviews with PM, PdM, developers, QA/testing, and Support / Operations
- Go/no-go decisions, release announcements, and known issues shared with stakeholders

### Decision Boundaries and Handoffs
- Coordinate the go/no-go review and record the decision with the accountable release approver agreed in the release plan; do not waive quality gates or change product priorities
- Hand deployment and rollback execution to developers and operations, and confirm post-release verification before closing the release

---

## Scrum Master / Delivery Facilitator

### Role Summary
Scrum Masters / Delivery Facilitators help the team maintain an effective delivery rhythm, remove process blockers, and improve collaboration.

### Responsibilities
- Facilitate standups, sprint planning, reviews, and retrospectives with developers and QA/testing
- Surface blockers, dependencies, and capacity constraints before they threaten commitments
- Work with the PM on delivery risks and with the PdM on backlog readiness
- Track retrospective actions and encourage sustainable execution

### Goals
- Improve delivery predictability and reduce blocked work
- Turn team feedback into practical process improvements

### Typical Communication
- Daily blocker triage and planning discussions with PM, PdM, developers, and QA/testing
- Sprint reviews with stakeholders and retrospective action follow-ups

### Decision Boundaries and Handoffs
- Facilitate team working agreements without owning product priority, assigning technical solutions, or changing project commitments
- Escalate unresolved cross-team blockers to the PM; hand priority trade-offs to the PdM and implementation estimates to developers and QA/testing

---

## Business Analyst

### Role Summary
Business Analysts translate stakeholder needs into clear requirements, workflows, and acceptance criteria that support planning and testing.

### Responsibilities
- Elicit stakeholder needs and document business rules, workflows, and edge cases
- Refine requirements and acceptance criteria with the PdM, developers, and QA/testing
- Identify requirement gaps and dependencies with the PM before work enters planning
- Support acceptance reviews by tracing delivered behavior to agreed requirements

### Goals
- Reduce ambiguity, rework, and missed acceptance scenarios
- Improve estimates and shared understanding of the intended outcome

### Typical Communication
- Requirements workshops with stakeholders and the PdM
- Backlog refinement with developers and QA/testing, plus scope-impact updates to the PM

### Decision Boundaries and Handoffs
- Clarify and document requirements; the PdM retains priority and product acceptance decisions, and the PM coordinates timeline impacts
- Hand agreed acceptance criteria to developers and QA/testing; route scope changes to the PdM rather than expanding work unilaterally

---

## Technical Lead / Architect

### Role Summary
Technical Leads / Architects guide technical direction and design trade-offs so implementation meets product needs and quality expectations.

### Responsibilities
- Define technical approaches, interfaces, and architectural constraints with developers
- Review designs for maintainability, security, performance, and operational readiness
- Support estimates and surface technical risks and dependencies to the PM
- Discuss feasibility and trade-offs with the PdM and stakeholders, and align test coverage with QA/testing

### Goals
- Reduce integration risks and costly design rework
- Enable maintainable implementation and technically ready releases

### Typical Communication
- Design reviews and technical decision records with developers and QA/testing
- Feasibility discussions with the PdM and stakeholders, and risk updates to the PM

### Decision Boundaries and Handoffs
- Guide technical decisions within agreed scope and constraints; route product trade-offs to the PdM and schedule or resource impacts to the PM
- Hand agreed designs to developers for implementation and review; coordinate verification with QA/testing and operational requirements with Support / Operations

---

## Support / Operations Representative

### Role Summary
Support / Operations Representatives bring production and customer-support experience into planning and help ensure releases can be operated and supported.

### Responsibilities
- Share incident trends, support feedback, and operational constraints with the PdM and developers
- Identify support-readiness tasks and operational risks with the PM during planning
- Review monitoring, runbooks, rollback procedures, and known issues with developers and the Release Manager
- Coordinate post-release verification with QA/testing and operations, and escalate production issues

### Goals
- Improve release stability, support readiness, and incident response
- Feed production lessons into future planning and prioritization

### Typical Communication
- Readiness checks with PM, developers, QA/testing, and the Release Manager
- Incident updates and support guidance for stakeholders, plus customer-impact feedback to the PdM

### Decision Boundaries and Handoffs
- Recommend operational readiness actions without changing product priorities or independently approving a release
- Hand critical production issues to on-call through the incident response process; coordinate rollback with developers and the Release Manager, and route follow-up work to the PdM and PM

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

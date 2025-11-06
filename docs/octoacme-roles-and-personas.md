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

## Engineers (QA)

### Role Summary
Engineers focused on quality assurance ensure that all features meet quality standards through comprehensive testing strategies, test automation, and defect management.

### Responsibilities
- Review acceptance criteria and develop test plans
- Execute manual and automated tests
- Track and report defects
- Collaborate with developers on fixes and regression testing
- Participate in release go/no-go decisions

### Goals
- Ensure product quality and stability
- Reduce production defects
- Increase test coverage and automation

### Typical Communication
- Test plan reviews with PM and engineers
- Bug reports and triage sessions
- Release readiness status updates

---

## Stakeholders

### Role Summary
Stakeholders include executives, business owners, and other teams who have a vested interest in project outcomes. They provide context, constraints, and approval for key decisions.

### Responsibilities
- Provide business context and constraints
- Review and approve project plans and changes
- Participate in key milestone reviews
- Escalate blockers and resource constraints

### Goals
- Ensure alignment with business objectives
- Manage budget and resource allocation
- Mitigate business risks

### Typical Communication
- Executive summaries and status reports
- Milestone reviews and sign-offs
- Escalation and decision meetings

---

## Release Manager

### Role Summary
The Release Manager coordinates all activities required to ship software safely and reliably to production. They act as the gatekeeper for releases, ensuring readiness, approvals, and coordination across teams. This role is critical for managing deployment risk and ensuring smooth production rollouts.

### Responsibilities
- Own the end-to-end release process and schedule
- Verify release readiness using checklists and quality gates
- Coordinate deployment activities across engineering, QA, and operations
- Manage rollback plans and post-release verification
- Communicate release status to stakeholders and coordinate deployment windows

### Goals
- Minimize production incidents and downtime
- Ensure predictable, repeatable release processes
- Maintain release velocity while managing risk

### RACI/Touchpoints
- **Reports to**: Project Manager or Engineering Manager
- **Coordinates with**: Engineers (build/deploy), QA Lead (test signoff), Communications Coordinator (stakeholder updates)
- **Approvals needed from**: QA Lead (test completion), Project Manager (release timing), Risk Owner (risk acceptance)
- **Accountable for**: Release execution, deployment success, rollback decisions

### Escalation Path
1. First: Project Manager (schedule conflicts, minor blockers)
2. Second: Engineering Manager + Risk Owner (technical issues, critical defects)
3. Final: Project Sponsor (go/no-go decisions, major delays)

### Why This Role Matters
The Release Manager ensures that releases don't introduce unnecessary risk to production systems. They maintain the discipline and rigor needed for safe deployments, coordinating across multiple teams to verify readiness and manage the end-to-end release lifecycle. Without this role, releases can become chaotic, leading to outages, missed rollback opportunities, and poor stakeholder communication.

---

## Risk Owner

### Role Summary
The Risk Owner identifies, tracks, and mitigates project risks. They maintain the risk register, ensure mitigation plans are in place, and escalate issues before they become critical. This role provides a systematic approach to risk management and ensures accountability.

### Responsibilities
- Maintain and review the risk register regularly
- Assign risk owners and track mitigation progress
- Facilitate risk assessment sessions with the team
- Escalate high-impact risks to stakeholders and leadership
- Define triggers for risk escalation and review cadence

### Goals
- Proactively identify and mitigate risks
- Prevent risks from becoming issues
- Maintain transparency around project exposure

### RACI/Touchpoints
- **Reports to**: Project Manager or Project Sponsor
- **Coordinates with**: Project Manager (risk integration into plans), Engineers (technical risks), QA Lead (quality risks)
- **Approvals needed from**: Project Sponsor (risk acceptance for high-impact items)
- **Accountable for**: Risk identification, mitigation tracking, escalation timing

### Escalation Path
1. First: Project Manager (medium-impact risks, mitigation support)
2. Second: Project Sponsor (high-impact risks, risk acceptance decisions)
3. Final: Executive Stakeholders (risks threatening project viability)

### Why This Role Matters
Projects often fail due to unmanaged risks that escalate into crises. The Risk Owner provides early warning systems and structured mitigation, preventing surprises and enabling proactive decision-making. This role ensures that risk management is not an afterthought but a continuous, accountable process throughout the project lifecycle.

---

## Project Sponsor

### Role Summary
The Project Sponsor is the executive-level champion who provides strategic direction, secures resources, and makes final decisions on scope, budget, and priorities. They are ultimately accountable for project success and alignment with organizational goals.

### Responsibilities
- Approve project charter, scope, and budget
- Provide strategic guidance and resolve conflicts
- Remove organizational barriers and secure resources
- Review major milestones and approve scope changes
- Make go/no-go decisions for releases and major deliverables

### Goals
- Ensure project delivers business value and ROI
- Align project with organizational strategy
- Manage stakeholder expectations at executive level

### RACI/Touchpoints
- **Reports to**: Executive Leadership or Board
- **Coordinates with**: Project Manager (status, decisions), Stakeholders (alignment), Risk Owner (risk acceptance)
- **Approvals needed from**: Executive Leadership (major budget/scope changes)
- **Accountable for**: Project success, ROI, strategic alignment

### Escalation Path
1. First: Direct escalation from Project Manager or Risk Owner
2. Final: Executive Leadership or Steering Committee

### Why This Role Matters
The Project Sponsor provides the authority and air cover needed to make difficult decisions, secure resources, and navigate organizational politics. Without executive sponsorship, projects can languish due to competing priorities, resource constraints, or lack of strategic clarity. This role ensures the project has the backing it needs to succeed.

---

## QA Lead

### Role Summary
The QA Lead defines the testing strategy, manages the QA team, and ensures quality standards are met before releases. They bridge product, engineering, and release management to verify that features meet acceptance criteria and are production-ready.

### Responsibilities
- Define test strategy and quality standards
- Review acceptance criteria with PM and engineers
- Manage test planning, execution, and defect triage
- Provide release readiness signoff to Release Manager
- Track quality metrics and identify improvement areas

### Goals
- Ensure high product quality and low defect rates
- Increase test coverage and automation
- Enable fast, confident releases

### RACI/Touchpoints
- **Reports to**: Engineering Manager or Quality Director
- **Coordinates with**: Product Managers (acceptance criteria), Engineers (test collaboration), Release Manager (release signoff)
- **Approvals needed from**: Engineering Manager (test strategy), Product Manager (acceptance criteria alignment)
- **Accountable for**: Test coverage, quality signoff, defect management

### Escalation Path
1. First: Engineering Manager (resource constraints, tooling needs)
2. Second: Product Manager + Release Manager (quality vs. timeline tradeoffs)
3. Final: Project Sponsor (go/no-go on quality concerns)

### Why This Role Matters
The QA Lead ensures that quality is built in, not bolted on. They provide the independent verification needed to catch defects before production and maintain the discipline to hold releases when quality bars are not met. This role is essential for maintaining customer trust and reducing the cost of post-release defects.

---

## Communications Coordinator

### Role Summary
The Communications Coordinator manages stakeholder communications, ensuring the right people get the right information at the right time. They craft messages, manage communication channels, and handle escalation messaging during incidents or delays.

### Responsibilities
- Map stakeholders and define communication cadence
- Draft status updates, executive summaries, and announcements
- Coordinate release communications and deployment notifications
- Manage escalation messaging during incidents
- Maintain communication channels and templates

### Goals
- Ensure stakeholder alignment and transparency
- Reduce communication overhead for the delivery team
- Provide timely, accurate information to stakeholders

### RACI/Touchpoints
- **Reports to**: Project Manager or Program Manager
- **Coordinates with**: Project Manager (status), Release Manager (deployment updates), Stakeholders (messaging needs)
- **Approvals needed from**: Project Manager (content approval), Project Sponsor (executive communications)
- **Accountable for**: Communication timing, message accuracy, stakeholder mapping

### Escalation Path
1. First: Project Manager (messaging conflicts, timing issues)
2. Second: Project Sponsor (executive communication escalations)

### Why This Role Matters
Poor communication leads to misalignment, surprises, and erosion of trust. The Communications Coordinator ensures that stakeholders are informed proactively, reducing noise and interruptions for the delivery team. This role is especially critical during incidents or delays, when clear, timely messaging can prevent panic and maintain confidence.

---

## Role Interaction Matrix

| Role | Reports To | Coordinates With | Requires Approval From | Key Handoffs |
|------|-----------|------------------|----------------------|--------------|
| **Developers** | Engineering Manager | PM (features), QA (testing), Project Manager (status) | Engineering Manager (design decisions) | Code to QA for testing |
| **Product Managers** | Product Director | Stakeholders (requirements), Engineers (feasibility), Project Manager (planning) | Stakeholders (priorities), Project Sponsor (roadmap) | Requirements to Engineers, acceptance criteria to QA Lead |
| **Project Managers** | Project Sponsor or PMO | All roles (coordination), Stakeholders (status) | Project Sponsor (scope changes) | Plans to team, status to Stakeholders |
| **Engineers (QA)** | QA Lead | Engineers (defects), PM (acceptance criteria) | QA Lead (test approach) | Test results to Release Manager |
| **Stakeholders** | Executive Leadership | Project Manager (input), Communications Coordinator (updates) | N/A | Requirements to PM, approvals to Project Sponsor |
| **Release Manager** | Project Manager or Engineering Manager | Engineers (deployment), QA Lead (signoff), Communications Coordinator (announcements) | QA Lead (quality), Project Manager (timing), Risk Owner (risk acceptance) | Release status to all stakeholders |
| **Risk Owner** | Project Manager or Project Sponsor | Project Manager (risks), Engineers (technical risks), QA Lead (quality risks) | Project Sponsor (risk acceptance) | Risk register to Project Manager, escalations to Project Sponsor |
| **Project Sponsor** | Executive Leadership | Project Manager (decisions), Stakeholders (alignment), Risk Owner (risks) | Executive Leadership (budget/scope changes) | Decisions to Project Manager, direction to team |
| **QA Lead** | Engineering Manager or Quality Director | PM (acceptance criteria), Engineers (testing), Release Manager (signoff) | Engineering Manager (strategy), PM (acceptance criteria) | Test signoff to Release Manager |
| **Communications Coordinator** | Project Manager or Program Manager | Project Manager (status), Release Manager (deployments), Stakeholders (feedback) | Project Manager (content), Project Sponsor (executive comms) | Updates to Stakeholders, announcements to all |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

**Implements**: #4


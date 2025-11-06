# QA Testing Guidelines

**Purpose**: Define QA Lead responsibilities, test planning process, and alignment with Product Manager and Release Manager.

**Owner**: QA Lead

**Implements**: #4

---

## QA Lead Responsibilities

The QA Lead ensures quality standards are met throughout the development lifecycle and provides release readiness signoff.

### Core Responsibilities

**Strategy & Planning**:
- Define overall test strategy and quality standards
- Review and approve test plans for features and releases
- Allocate testing resources across projects
- Establish quality metrics and reporting

**Team Leadership**:
- Manage and mentor QA team members
- Conduct test plan reviews and knowledge sharing
- Coordinate test automation initiatives
- Foster quality culture across engineering

**Stakeholder Collaboration**:
- Align with Product Manager on acceptance criteria
- Coordinate with Release Manager on release readiness
- Report quality metrics to Project Manager and stakeholders
- Escalate quality risks to Project Sponsor when needed

**Release Signoff**:
- Verify all test cases executed and passed
- Review defect trends and severity
- Provide go/no-go recommendation to Release Manager
- Sign off on release readiness checklist

---

## Test Plan Checklist

Use this checklist when creating a test plan for a feature, sprint, or release.

### 1. Requirements Review
- [ ] User stories and requirements reviewed with Product Manager
- [ ] Acceptance criteria clearly defined and testable
- [ ] Edge cases and error scenarios identified
- [ ] Non-functional requirements captured (performance, security, etc.)
- [ ] Dependencies on other features or systems noted

### 2. Test Scope Definition
- [ ] In-scope features and functionalities listed
- [ ] Out-of-scope items documented with rationale
- [ ] Test environments identified (dev, staging, production)
- [ ] Test data requirements defined
- [ ] Browser/platform/device coverage specified

### 3. Test Strategy
- [ ] Test types defined (unit, integration, E2E, regression, performance, security)
- [ ] Manual vs. automated testing approach determined
- [ ] Risk-based testing priorities identified
- [ ] Exploratory testing sessions planned
- [ ] Load/stress testing requirements (if applicable)

### 4. Test Cases
- [ ] Test cases written and reviewed
- [ ] Positive and negative test scenarios covered
- [ ] Boundary and edge cases included
- [ ] Test data and preconditions specified
- [ ] Expected results clearly defined

### 5. Automation
- [ ] Automation candidates identified
- [ ] Automation framework and tools selected
- [ ] Automated test scripts written and reviewed
- [ ] Automated tests integrated into CI/CD pipeline
- [ ] Automation coverage metrics tracked

### 6. Resources & Schedule
- [ ] QA resources allocated (who will test what)
- [ ] Testing timeline defined with milestones
- [ ] Test environment availability confirmed
- [ ] Tools and licenses available
- [ ] Coordination with engineers for environment setup

### 7. Defect Management
- [ ] Defect tracking process defined
- [ ] Severity and priority levels established
- [ ] Defect triage process agreed with team
- [ ] Retest and regression testing approach defined
- [ ] Defect metrics and reporting cadence set

### 8. Exit Criteria
- [ ] Pass rate threshold defined (e.g., 95% of test cases pass)
- [ ] No open critical or high-severity defects
- [ ] All acceptance criteria met
- [ ] Performance benchmarks met (if applicable)
- [ ] Security scans passed (if applicable)

---

## Acceptance Criteria Alignment

Ensure acceptance criteria are clear, testable, and aligned between PM, Engineering, and QA.

### Acceptance Criteria Review Checklist

- [ ] **Specific**: Criteria are clear and unambiguous
- [ ] **Measurable**: Success can be objectively verified
- [ ] **Achievable**: Criteria can be implemented and tested in the sprint
- [ ] **Relevant**: Criteria align with user story goals
- [ ] **Testable**: QA can write test cases to verify each criterion

### Example of Good Acceptance Criteria

**User Story**: As a user, I want to reset my password so I can regain access to my account.

**Acceptance Criteria**:
- [ ] User can request password reset from login page
- [ ] Reset email sent within 5 minutes of request
- [ ] Reset link expires after 24 hours
- [ ] User can set a new password meeting complexity requirements (8+ chars, 1 number, 1 special char)
- [ ] Old password cannot be reused
- [ ] User is logged in automatically after successful reset
- [ ] Error message shown if reset link is expired or invalid

---

## QA/PM/Release Manager Touchpoints

### Sprint Planning (with PM and Engineers)

**QA Lead Activities**:
- [ ] Review upcoming user stories and acceptance criteria
- [ ] Provide test effort estimates
- [ ] Identify testability concerns early
- [ ] Ensure Definition of Done includes QA signoff

**Outputs**:
- Test effort estimates for sprint backlog items
- Testing risks and dependencies flagged

---

### Mid-Sprint Check-ins (with PM)

**QA Lead Activities**:
- [ ] Review progress on test execution
- [ ] Discuss any acceptance criteria ambiguities
- [ ] Coordinate on defect prioritization
- [ ] Align on scope changes or new requirements

**Outputs**:
- Updated test status
- Clarified acceptance criteria
- Defect triage decisions

---

### Pre-Release Review (with Release Manager and PM)

**QA Lead Activities**:
- [ ] Present test results and coverage metrics
- [ ] Review open defects by severity
- [ ] Provide release readiness recommendation
- [ ] Discuss any quality risks for release

**Outputs**:
- Release readiness signoff (Go/No-Go)
- Known issues documented for release notes
- Post-release test plan (if needed)

---

### Post-Release (with PM, Release Manager, Engineers)

**QA Lead Activities**:
- [ ] Monitor production issues and customer reports
- [ ] Conduct smoke testing in production
- [ ] Review defect trends and root causes
- [ ] Identify test gaps and process improvements

**Outputs**:
- Post-release quality report
- Lessons learned for next release
- Test automation backlog items

---

## Quality Metrics & Reporting

Track and report these metrics to provide visibility into quality trends.

### Test Execution Metrics
- **Test Cases Executed**: _____ / _____
- **Pass Rate**: _____%
- **Test Coverage**: _____% (lines of code, requirements, etc.)
- **Automated Test Coverage**: _____%

### Defect Metrics
- **Total Defects Found**: _____
- **Critical Defects**: _____
- **High Priority Defects**: _____
- **Defects by Module/Feature**: (breakdown)
- **Defect Detection Rate**: _____ defects per story point
- **Defect Escape Rate**: _____ defects found in production

### Trend Analysis
- **Defect Trends**: (increasing/decreasing over sprints)
- **Test Automation Growth**: (% of tests automated over time)
- **Test Execution Time**: (time to run full regression)

---

## Release Readiness Signoff Template

**Release**: [Version/Name]

**Target Release Date**: [Date]

**QA Lead**: [Name]

**Date**: [Date]

---

### Test Execution Summary

| Test Type | Planned | Executed | Passed | Failed | Pass Rate |
|-----------|---------|----------|--------|--------|-----------|
| Unit Tests | | | | | % |
| Integration Tests | | | | | % |
| E2E Tests | | | | | % |
| Regression Tests | | | | | % |
| Performance Tests | | | | | % |
| Security Tests | | | | | % |

**Overall Test Pass Rate**: _____%

---

### Defect Summary

| Severity | Open | Resolved | Deferred | Notes |
|----------|------|----------|----------|-------|
| Critical | | | | |
| High | | | | |
| Medium | | | | |
| Low | | | | |

**Total Open Defects**: _____

**Defects Deferred to Next Release**: _____ (with Product Manager approval)

---

### Acceptance Criteria Status

- [ ] All user stories have passing acceptance tests
- [ ] All acceptance criteria verified and documented
- [ ] No unresolved blockers or dependencies
- [ ] Performance benchmarks met
- [ ] Security scans completed with no critical findings

---

### Release Risks

**Quality Risks Identified**:
1. (Risk and mitigation/acceptance decision)
2. (Risk and mitigation/acceptance decision)
3. (Risk and mitigation/acceptance decision)

---

### Recommendation

**Release Readiness**: ☐ **GO** ☐ **NO-GO** ☐ **GO with Conditions**

**Rationale**:
(Provide reasoning for recommendation, including any conditions or caveats)

**Conditions (if applicable)**:
- (List any conditions that must be met for release)

**Known Issues for Release Notes**:
- (List any known issues that should be communicated to users)

---

### Sign-Off

**QA Lead Signature**: _________________________ **Date**: _________

**Product Manager Acknowledgment**: _________________________ **Date**: _________

**Release Manager Acknowledgment**: _________________________ **Date**: _________

---

## Testing Best Practices

### Test-First Mindset
- Involve QA from story refinement through delivery
- Write test cases before code is complete (based on acceptance criteria)
- Use test cases to validate understanding of requirements

### Risk-Based Testing
- Prioritize testing based on business impact and risk
- Focus on critical user journeys and high-risk areas
- Use production metrics to guide test prioritization

### Shift-Left Testing
- Test as early as possible in the development cycle
- Provide fast feedback to engineers (unit tests, static analysis)
- Catch defects before they propagate downstream

### Continuous Testing
- Integrate automated tests into CI/CD pipeline
- Run tests on every commit and pull request
- Monitor test results and trends continuously

### Collaboration
- Pair with developers on test strategy
- Participate in design reviews to identify testability issues
- Maintain open communication with PM and Release Manager

---

## Related Documents

- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md)
- [Release Checklist](release-checklist.md)
- [OctoAcme Project Planning](octoacme-project-planning.md)
- [OctoAcme Execution and Tracking](octoacme-execution-and-tracking.md)

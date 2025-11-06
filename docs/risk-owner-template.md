# Risk Owner Template

**Purpose**: Provide a structured approach to capturing, tracking, and mitigating project risks.

**Owner**: Risk Owner

**Implements**: #4

---

## Risk Register Overview

The risk register is a living document that captures all identified risks, their impact, probability, and mitigation plans. The Risk Owner maintains this register and ensures regular reviews and updates.

### Review Cadence
- **Weekly**: Review with Project Manager during status meetings
- **Sprint Planning**: Review with delivery team to identify new technical risks
- **Monthly**: Review with Project Sponsor for high-impact risks
- **Pre-Release**: Full risk assessment with Release Manager

---

## Risk Capture Template

Use this template for each identified risk in the register.

### Risk ID: [R-XXX]

**Risk Title**: (Short, descriptive title)

**Date Identified**: YYYY-MM-DD

**Identified By**: (Name/Role)

**Risk Owner**: (Name/Role assigned to manage this specific risk)

---

### Risk Description

(Clear description of the risk, including what could go wrong and under what conditions)

**Example**: "Third-party API provider has no SLA and history of outages. If their service goes down during our launch window, our checkout flow will fail, impacting revenue."

---

### Risk Assessment

**Impact**: ☐ Low ☐ Medium ☐ High ☐ Critical

**Probability**: ☐ Low (< 25%) ☐ Medium (25-50%) ☐ High (50-75%) ☐ Very High (> 75%)

**Risk Score**: (Impact × Probability) = _______

**Category**: ☐ Technical ☐ Schedule ☐ Resource ☐ External ☐ Quality ☐ Security ☐ Business

---

### Impact Analysis

**If this risk occurs**:
- **Customer Impact**: (How will end-users be affected?)
- **Business Impact**: (Revenue, reputation, compliance, etc.)
- **Timeline Impact**: (Will this delay the project? By how long?)
- **Team Impact**: (Does this affect team morale, capacity, or other work?)

---

### Mitigation Plan

**Preventive Actions** (reduce probability):
1. (Action to prevent risk from occurring)
2. (Action to prevent risk from occurring)
3. (Action to prevent risk from occurring)

**Contingency Actions** (reduce impact if risk occurs):
1. (Action to minimize damage if risk happens)
2. (Action to minimize damage if risk happens)
3. (Action to minimize damage if risk happens)

**Owner of Mitigation**: (Name/Role)

**Mitigation Due Date**: YYYY-MM-DD

**Status**: ☐ Not Started ☐ In Progress ☐ Completed ☐ Blocked

---

### Escalation Triggers

Escalate this risk when any of the following occur:

- [ ] Probability increases to High or Very High
- [ ] Impact increases to High or Critical
- [ ] Mitigation actions blocked or ineffective
- [ ] Risk materializes (becomes an issue)
- [ ] Timeline impact > _____ days
- [ ] Cost impact > $ _______
- [ ] Custom trigger: _______________________

---

### Escalation Path

**Level 1**: Project Manager
- **When**: Probability or Impact = Medium
- **Action**: Discuss mitigation options, adjust project plan

**Level 2**: Project Sponsor + Risk Owner
- **When**: Probability or Impact = High, or mitigation blocked
- **Action**: Review risk acceptance, allocate resources, adjust scope/timeline

**Level 3**: Executive Leadership
- **When**: Impact = Critical, or risk threatens project viability
- **Action**: Strategic decision on project continuation, major scope/budget changes

---

### Risk Acceptance

If mitigation is not feasible or cost-effective, the risk may be accepted.

**Accepted By**: (Name/Role - typically Project Sponsor)

**Acceptance Date**: YYYY-MM-DD

**Acceptance Rationale**: (Why is this risk being accepted? What is the business justification?)

**Monitoring Plan**: (How will we monitor this risk even though it's accepted?)

---

## Risk Register Summary Table

Maintain a summary table of all active risks for quick reference and stakeholder reporting.

| Risk ID | Title | Owner | Impact | Probability | Score | Status | Last Updated |
|---------|-------|-------|--------|-------------|-------|--------|--------------|
| R-001 | | | | | | | |
| R-002 | | | | | | | |
| R-003 | | | | | | | |

**Risk Legend**:
- **Impact**: L = Low, M = Medium, H = High, C = Critical
- **Probability**: L = Low, M = Medium, H = High, VH = Very High
- **Status**: Open, Mitigating, Closed, Accepted

---

## Review Checklist

Use this checklist during regular risk reviews:

- [ ] All open risks reviewed and status updated
- [ ] New risks identified and added to register
- [ ] Mitigation actions tracked and owners confirmed
- [ ] Closed risks verified and documented
- [ ] High/Critical risks escalated appropriately
- [ ] Risk trends analyzed (are risks increasing or decreasing?)
- [ ] Stakeholders informed of material changes
- [ ] Risk register exported and shared with Project Manager

---

## Risk Communication

### Weekly Status Template

**To**: Project Manager, Delivery Team

**Subject**: Weekly Risk Update - [Project Name]

**Summary**:
- Total Active Risks: _____
- New Risks This Week: _____
- Risks Closed This Week: _____
- High/Critical Risks: _____

**Top 3 Risks**:
1. [Risk ID]: [Title] - [Status] - [Owner]
2. [Risk ID]: [Title] - [Status] - [Owner]
3. [Risk ID]: [Title] - [Status] - [Owner]

**Escalations Needed**: (List any risks requiring executive attention)

**Actions Required**: (List any specific actions needed from recipients)

---

### Monthly Executive Summary Template

**To**: Project Sponsor, Stakeholders

**Subject**: Monthly Risk Summary - [Project Name]

**Risk Trend**: ☐ Improving ☐ Stable ☐ Worsening

**Key Highlights**:
- (Summary of risk posture and major changes)

**Critical Risks Requiring Attention**:
- (List risks needing executive decision or resources)

**Risk Acceptance Decisions Needed**:
- (List risks recommended for acceptance with rationale)

---

## Related Documents

- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md)
- [Release Checklist](release-checklist.md)
- [OctoAcme Risks and Communication](octoacme-risks-and-communication.md)

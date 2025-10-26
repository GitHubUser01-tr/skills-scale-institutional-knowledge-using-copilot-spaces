# Change Request Form Template

## Purpose
Document and track changes to production systems, ensuring proper review, approval, and implementation procedures are followed.

## How to Use
1. Copy this template or create a new change request using your project's issue tracker
2. Fill in all required fields before submitting for review
3. Attach any supporting documentation (test plans, rollback procedures, etc.)
4. Submit to Change Control Coordinator for review and scheduling

---

## Change Request Information

**Change Request ID:** [Auto-generated or CR-YYYY-MM-NNN]  
**Submitted By:** [Name]  
**Submitted Date:** [Date]  
**Requested Implementation Date:** [Date]  
**Priority:** [ ] Low [ ] Medium [ ] High [ ] Emergency

---

## Change Details

### Change Title
[Brief, descriptive title of the change]

### Change Description
[Detailed description of what is being changed and why]

### Change Type
- [ ] Standard (pre-approved, low-risk change)
- [ ] Normal (requires standard approval process)
- [ ] Emergency (requires expedited approval due to critical issue)

### Change Category
- [ ] New Feature
- [ ] Enhancement
- [ ] Bug Fix
- [ ] Configuration Change
- [ ] Infrastructure Update
- [ ] Security Patch
- [ ] Other: [Specify]

### Business Justification
[Why is this change necessary? What business value does it provide?]

### Affected Systems/Components
[List all systems, services, or components that will be affected]
- 
- 
- 

---

## Impact Assessment

### User Impact
- [ ] No user impact
- [ ] Minimal user impact (brief performance degradation)
- [ ] Moderate user impact (some features unavailable)
- [ ] Significant user impact (major features unavailable)
- [ ] Service outage required

**Impact Details:**
[Describe specific impact to users]

### Downtime Required
- [ ] No downtime
- [ ] Minimal (<5 minutes)
- [ ] Moderate (5-30 minutes)
- [ ] Extended (>30 minutes)

**Downtime Window:** [Date/Time - Date/Time]

### Dependencies
[List any dependencies on other changes, systems, or teams]
- 
- 

---

## Implementation Plan

### Implementation Steps
1. [Step 1]
2. [Step 2]
3. [Step 3]
[Continue as needed]

### Implementation Team
- **Primary Implementer:** [Name]
- **Secondary/Backup:** [Name]
- **Technical Lead:** [Name]

### Implementation Duration
**Estimated Time:** [X hours/minutes]  
**Implementation Window:** [Start Time] - [End Time]

---

## Testing & Validation

### Testing Completed
- [ ] Unit tests passed
- [ ] Integration tests passed
- [ ] User acceptance testing completed
- [ ] Performance testing completed
- [ ] Security testing completed

**Test Results Summary:**
[Brief summary of test results or link to test report]

### QA Sign-off
**QA Lead:** [Name]  
**Sign-off Date:** [Date]  
**Notes:** [Any relevant notes]

### Validation Criteria
[How will you verify the change was successful?]
- 
- 
- 

---

## Risk Assessment

### Risk Level
- [ ] Low (minimal impact if it fails)
- [ ] Medium (moderate impact, recoverable)
- [ ] High (significant impact, difficult to recover)

### Identified Risks
[List potential risks associated with this change]
1. 
2. 
3. 

### Mitigation Strategies
[For each risk, describe mitigation approach]
1. 
2. 
3. 

---

## Rollback Plan

### Rollback Procedure
[Detailed steps to rollback if the change fails]
1. [Step 1]
2. [Step 2]
3. [Step 3]

### Rollback Trigger Criteria
[What conditions would trigger a rollback?]
- 
- 

### Rollback Time Estimate
**Estimated Time:** [X hours/minutes]

### Rollback Team
- **Primary:** [Name]
- **Secondary:** [Name]

---

## Communication Plan

### Stakeholders to Notify
- [ ] Engineering Team
- [ ] Product Team
- [ ] Operations/Support
- [ ] Customers/End Users
- [ ] Executive Leadership
- [ ] Other: [Specify]

### Pre-Implementation Communication
**Notification Date:** [Date]  
**Communication Method:** [Email/Slack/Status Page/etc.]  
**Communication Owner:** [Name]

### Post-Implementation Communication
**Completion Notification:** [When/How will completion be communicated?]

---

## Approvals

### Required Approvals
- [ ] **Change Control Coordinator:** [Name] - Date: ______
- [ ] **Technical Lead:** [Name] - Date: ______
- [ ] **QA Lead:** [Name] - Date: ______
- [ ] **Project Manager:** [Name] - Date: ______
- [ ] **Risk Manager:** [Name] - Date: ______ (for high-risk changes)

### Change Advisory Board (CAB) Review
**CAB Meeting Date:** [Date]  
**CAB Decision:** [ ] Approved [ ] Rejected [ ] Deferred  
**CAB Notes:**
[Any notes or conditions from CAB review]

---

## Post-Implementation Review

### Implementation Status
- [ ] Successful
- [ ] Successful with issues
- [ ] Failed (rollback completed)
- [ ] Partially successful

### Implementation Date/Time
**Start:** [Date/Time]  
**End:** [Date/Time]  
**Actual Duration:** [X hours/minutes]

### Validation Results
[Did the change achieve the desired outcome?]
- 
- 

### Issues Encountered
[Any issues or unexpected outcomes during implementation?]
- 
- 

### Lessons Learned
[What went well? What could be improved for future changes?]
- 
- 

### Post-Implementation Review Sign-off
**Reviewer:** [Name]  
**Review Date:** [Date]  
**Status:** [ ] Closed [ ] Follow-up Required

---

## Supporting Documentation

### Attached Documents
- [ ] Technical design document
- [ ] Test plan and results
- [ ] Rollback procedure document
- [ ] Configuration files
- [ ] Other: [Specify]

**Document Links:**
- [Document 1]: [Link]
- [Document 2]: [Link]

---

## Notes and Comments
[Additional notes, comments, or context]

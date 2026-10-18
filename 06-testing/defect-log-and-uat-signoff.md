# Defect Log and UAT Sign-Off: Supply Chain Process Improvement

## 1. Purpose

This document provides templates for recording defects identified during User Acceptance Testing (UAT) and documenting the business decision on whether the solution is ready for acceptance.

The examples relate to a fictional manufacturing company's procurement and goods receipt processes.

## 2. Defect Log

A defect is a difference between the expected behaviour and the actual behaviour observed during testing.

| Defect ID | Related Test | Description | Severity | Priority | Status |
|---|---|---|---|---|---|
| DEF-001 | UAT-003 | Outstanding purchase order quantity is not displayed correctly after a partial receipt | High | High | Open |
| DEF-002 | UAT-005 | Invoice quantity discrepancy is not clearly flagged for investigation | High | High | Open |
| DEF-003 | UAT-007 | Supply chain report does not include all agreed KPI fields | Medium | Medium | Open |

These are illustrative defects for the portfolio, not issues discovered in a live ERP system.

## 3. Information to Record for Each Defect

Each defect record should include:

- Defect ID and date raised.
- Related requirement and test case.
- Environment and relevant test data.
- Steps to reproduce the problem.
- Expected result.
- Actual result.
- Supporting evidence, such as screenshots where permitted.
- Severity and priority.
- Assigned owner.
- Current status and resolution notes.
- Retest result and closure date.

## 4. Severity and Priority

Severity describes the impact of the defect on the system or business process. Priority describes how urgently it should be addressed.

| Classification | Example |
|---|---|
| High Severity | A critical business control does not work as required |
| Medium Severity | A significant function is affected, but a workaround may exist |
| Low Severity | A minor problem has limited operational impact |
| High Priority | The defect requires urgent attention before a key milestone |
| Medium Priority | The defect should be resolved within an agreed timeframe |
| Low Priority | The defect can be addressed later if approved |

The project team should agree the classification criteria. Severity and priority do not always have to be identical.

## 5. Defect Management Process

1. A UAT participant executes a test case.
2. The participant records the actual result and compares it with the expected result.
3. If the results differ, the tester records a defect with reproducible steps and supporting evidence.
4. The relevant team reviews the defect, confirms its validity and assigns severity, priority and ownership.
5. The technical team investigates and resolves the defect, or records an agreed alternative disposition.
6. The tester retests the affected scenario.
7. Related regression tests are performed where necessary.
8. The defect is closed only when the agreed closure criteria are met.

A workaround, deferral or acceptance of a known defect must follow the organisation's approval process.

## 6. UAT Exit Criteria

Before UAT can be considered complete, the project team should confirm that:

- The agreed UAT scenarios have been executed or formally accounted for.
- Results and supporting evidence have been recorded.
- Critical defects have been resolved and retested, according to agreed criteria.
- Remaining defects have been assessed and their disposition approved by authorised stakeholders.
- Business requirements and acceptance criteria have been reviewed.
- Outstanding risks and limitations have been communicated.
- The appropriate business representative has made the acceptance decision.

The exact exit criteria must be agreed before testing begins.

## 7. UAT Sign-Off Template

### Project Information

| Field | Details |
|---|---|
| Project | Supply Chain Process Improvement |
| Business Area | Procurement, Warehouse and Finance |
| UAT Period | To be agreed |
| Test Environment | To be confirmed |
| Business Approver | To be assigned |

### Acceptance Decision

Select one of the following decisions when the template is used for a real project:

- Accepted: Agreed acceptance criteria have been met.
- Accepted with Approved Outstanding Items: Remaining defects or limitations have documented decisions and authorised acceptance.
- Not Accepted: Material issues prevent acceptance.

### Sign-Off Record

| Field | Details |
|---|---|
| Decision | To be completed |
| Outstanding Defects | To be documented |
| Known Limitations | To be documented |
| Conditions or Actions | To be documented |
| Approver Name and Role | To be completed |
| Approval Date | To be completed |
| Evidence Reference | To be recorded |

No sign-off has been obtained for this fictional case study. This section is a reusable template.

## 8. Business Analyst Responsibilities

The Business Analyst helps ensure that test cases trace back to requirements, business users understand expected outcomes, defects are documented clearly and stakeholders can make informed acceptance decisions.

The Business Analyst may facilitate defect review meetings, clarify requirements and coordinate retesting. Technical investigation and formal acceptance remain the responsibility of the relevant assigned team members and authorised approvers.

## 9. Conclusion

A structured defect log and UAT sign-off process improve transparency, accountability and confidence in business acceptance. They also help ensure that unresolved defects and known limitations are understood before a deployment decision is made.

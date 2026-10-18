# Requirements Traceability Matrix (RTM)

## 1. Purpose

The Requirements Traceability Matrix links business requirements to user stories and UAT test cases. It helps confirm that each requirement has a corresponding validation activity.

## 2. Traceability Matrix

| Requirement ID | Business Requirement | User Story | UAT Test Case | Coverage |
|---|---|---|---|---|
| BR-001 | Purchase order visibility | US-001 | UAT-001 | Covered |
| BR-002 | Goods receipt recording | US-002 | UAT-002, UAT-003 | Covered |
| BR-003 | Inventory updates | US-002 | UAT-002, UAT-003 | Partially covered |
| BR-004 | Supplier invoice matching | US-003 | UAT-004, UAT-005 | Covered |
| BR-005 | Exception management | US-003 | UAT-005, UAT-006 | Covered |
| BR-006 | Supply chain reporting | US-004 | UAT-007 | Covered |
| NFR-001 | Access control | Not yet linked | UAT-008 | Partially covered |
| NFR-002 | Auditability | Not yet linked | Not yet defined | Gap identified |
| NFR-003 | Data quality | Not yet linked | Not yet defined | Gap identified |

## 3. Traceability Review

The matrix identifies requirements that need additional coverage.

- BR-003 requires a dedicated inventory update validation scenario.
- NFR-001 needs a corresponding user story or functional requirement where appropriate.
- NFR-002 requires a test to verify that relevant transactions and changes can be traced.
- NFR-003 requires tests for mandatory fields, invalid data and data consistency.

## 4. Change Impact Analysis

If a business requirement changes, the Business Analyst should identify the affected user stories, process diagrams, test cases and related documentation.

For example, if the agreed invoice matching tolerance changes, the invoice matching requirements, acceptance criteria and UAT scenarios may all need updating.

## 5. Definition of Complete Coverage

A requirement is considered fully traced when it has an appropriate implementation or solution reference, test coverage and a recorded outcome where testing has been performed.

Coverage in this document refers to documented test links, not successful execution.

## 6. Status

This is an illustrative traceability matrix for a learning portfolio. Coverage and test status must be updated as requirements and test scenarios are refined.

# User Stories and Acceptance Criteria

## Project

Supply Chain Process Improvement using Microsoft Dynamics 365 Finance & Operations concepts

## User Story 1: View Purchase Order Status

**ID:** US-001

**As a** procurement team member,

**I want** to view purchase order status and expected delivery dates,

**So that** I can coordinate with suppliers and help the warehouse prepare for incoming deliveries.

### Acceptance Criteria

1. Given a purchase order exists, when an authorised user views the order, the current status is displayed.
2. Given an expected delivery date has been recorded, the date is visible to authorised users.
3. Given a purchase order is overdue and remains outstanding, it can be identified in the relevant report.

## User Story 2: Record Goods Receipt

**ID:** US-002

**As a** warehouse team member,

**I want** to record the actual quantity of goods received against a purchase order,

**So that** inventory records reflect the goods physically received.

### Acceptance Criteria

1. Given an open purchase order exists, when the warehouse receives goods, the user can record the received quantity.
2. Given the supplier delivers fewer units than ordered, the recorded receipt reflects the actual quantity received.
3. Given a receipt has been successfully recorded, the relevant inventory and purchasing records reflect the transaction according to the configured process.

## User Story 3: Identify Supplier Invoice Discrepancies

**ID:** US-003

**As an** accounts payable analyst,

**I want** to compare supplier invoices with purchase orders and goods receipts,

**So that** discrepancies can be investigated before payment approval.

### Acceptance Criteria

1. Given a supplier invoice is entered, the relevant purchase order and goods receipt can be identified for matching.
2. Given a quantity or price discrepancy exceeds an agreed tolerance, the invoice is flagged for review.
3. Given an exception is identified, the responsible team can investigate and record its resolution.
4. An invoice proceeds through the applicable approval process only when required controls are satisfied.

## User Story 4: Monitor Supply Chain Exceptions

**ID:** US-004

**As a** supply chain manager,

**I want** to review outstanding purchase orders, overdue deliveries and unresolved discrepancies,

**So that** I can prioritise operational issues and take corrective action.

### Acceptance Criteria

1. The report identifies outstanding purchase orders.
2. Overdue deliveries can be distinguished from deliveries that are not yet overdue.
3. Unresolved discrepancies can be identified for follow-up.
4. Reported information is consistent with the underlying business records.

## Business Analyst Notes

These user stories describe intended business outcomes rather than specific technical implementations.

The acceptance criteria must be reviewed with stakeholders and refined to reflect agreed business rules, permissions, matching tolerances and reporting requirements.

## Traceability

- US-001 supports BR-001.
- US-002 supports BR-002 and BR-003.
- US-003 supports BR-004 and BR-005.
- US-004 supports BR-006.

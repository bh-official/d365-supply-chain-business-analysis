# User Acceptance Testing (UAT) Test Cases

## Project

Supply Chain Process Improvement using Microsoft Dynamics 365 Finance & Operations concepts

## 1. Purpose

These test cases demonstrate how business users could validate the proposed procurement, goods receipt and supplier invoice matching processes.

The scenarios are illustrative and would need to be executed in an appropriate test environment before any real implementation could be accepted.

## 2. Test Case Summary

| Test ID | Requirement | Scenario | Expected Result |
|---|---|---|---|
| UAT-001 | BR-001 | View an existing purchase order | Order status and expected delivery date are visible to authorised users |
| UAT-002 | BR-002 | Receive the full ordered quantity | Actual receipt quantity is recorded correctly |
| UAT-003 | BR-002 | Receive a partial delivery | Actual quantity is recorded and the outstanding quantity can be identified |
| UAT-004 | BR-004 | Process an invoice matching the order and receipt | Invoice passes the configured matching checks |
| UAT-005 | BR-004, BR-005 | Process an invoice with a quantity discrepancy | Invoice is flagged when the discrepancy exceeds the agreed tolerance |
| UAT-006 | BR-005 | Investigate a flagged discrepancy | The exception can be investigated and its resolution recorded |
| UAT-007 | BR-006 | Review outstanding purchase orders | The report identifies outstanding orders and overdue deliveries |
| UAT-008 | NFR-001 | Attempt an action without the required permission | Access is denied in accordance with the configured security rules |

## 3. Detailed Test Scenarios

### UAT-001: Purchase Order Visibility

**Precondition:** A purchase order exists with an expected delivery date.

**Steps:**
1. Sign in as an authorised procurement user.
2. Open the relevant purchase order.
3. Review the order status and expected delivery date.

**Expected result:** The correct status and date are displayed.

### UAT-002: Full Goods Receipt

**Precondition:** A purchase order exists for 100 units and the supplier delivers all 100 units.

**Steps:**
1. Open the purchase order.
2. Record the receipt of 100 units.
3. Confirm the receipt according to the configured process.
4. Review the receipt and relevant inventory records.

**Expected result:** The recorded receipt reflects 100 units and the related records are updated as intended.

### UAT-003: Partial Goods Receipt

**Precondition:** A purchase order exists for 100 units, but the supplier delivers 80 units.

**Steps:**
1. Open the purchase order.
2. Record the receipt of 80 units.
3. Review the remaining order quantity.
4. Check whether the outstanding quantity can be identified for follow-up.

**Expected result:** The receipt records 80 units, and the remaining 20 units can be tracked according to the order and delivery rules.

### UAT-004: Matching Supplier Invoice

**Precondition:** A purchase order and goods receipt exist for the invoiced quantity and price.

**Steps:**
1. Enter or review the supplier invoice in the test environment.
2. Compare the invoice against the purchase order and goods receipt.
3. Run the applicable matching checks.

**Expected result:** The invoice passes the configured matching checks when all applicable conditions are satisfied.

### UAT-005: Invoice Quantity Discrepancy

**Precondition:** The purchase order is for 100 units, the goods receipt records 80 units and the invoice requests payment for 100 units.

**Steps:**
1. Enter the invoice in the test environment.
2. Compare the invoice quantity with the recorded receipt.
3. Review the configured matching rules and any resulting exception.

**Expected result:** The discrepancy is identified when it exceeds the agreed matching tolerance, and the invoice follows the required exception and approval process.

### UAT-006: Resolve an Exception

**Precondition:** An invoice discrepancy has been flagged.

**Steps:**
1. Review the purchase order, receipt and invoice.
2. Identify the cause of the discrepancy.
3. Record the investigation outcome.
4. Follow the approved correction or exception process.

**Expected result:** The exception has a documented outcome and the invoice proceeds only when the required controls are satisfied.

### UAT-007: Supply Chain Reporting

**Precondition:** Test data includes open purchase orders, overdue deliveries and unresolved discrepancies.

**Steps:**
1. Open the relevant report.
2. Review the listed orders and exceptions.
3. Compare the report against the underlying test records.

**Expected result:** The report correctly identifies the relevant orders and exceptions.

### UAT-008: Access Control

**Precondition:** A test user does not have permission to perform a restricted action.

**Steps:**
1. Sign in using the test account.
2. Attempt the restricted action.
3. Record the system response.

**Expected result:** The user cannot perform the restricted action.

## 4. Test Execution Record

| Test ID | Actual Result | Status | Defect Reference |
|---|---|---|---|
| UAT-001 | Not executed | Not Run | N/A |
| UAT-002 | Not executed | Not Run | N/A |
| UAT-003 | Not executed | Not Run | N/A |
| UAT-004 | Not executed | Not Run | N/A |
| UAT-005 | Not executed | Not Run | N/A |
| UAT-006 | Not executed | Not Run | N/A |
| UAT-007 | Not executed | Not Run | N/A |
| UAT-008 | Not executed | Not Run | N/A |

## 5. Exit Criteria

- All agreed high-priority test cases have been executed.
- Critical defects have been resolved or formally accepted by the appropriate decision-maker.
- Failed tests have been investigated and retested where applicable.
- Business stakeholders review the results and provide the required sign-off.

## 6. Important Note

These test cases are portfolio examples, not evidence of actual execution in Microsoft Dynamics 365. Actual results must be recorded only after testing in an appropriate environment.

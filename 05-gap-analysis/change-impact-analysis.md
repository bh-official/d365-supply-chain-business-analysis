# Change Impact Analysis: Supply Chain Process Improvement

## 1. Purpose

Change impact analysis helps a Business Analyst understand the consequences of a proposed change before it is approved or implemented.

This document uses a fictional manufacturing company to demonstrate how a change to the goods receipt process could affect business requirements, workflows, testing, reporting and stakeholders.

## 2. Example Change Request

**Change ID:** CR-001

**Title:** Introduce partial goods receipt recording.

**Change description:** The warehouse team needs to record goods received in multiple deliveries against a single purchase order, rather than treating the order as fully received after the first delivery.

**Business reason:** Suppliers may deliver only part of an order initially. Accurate receipt records are needed to show what has arrived and what remains outstanding.

## 3. Impact Assessment

| Area | Potential Impact | Action Required |
|---|---|---|
| Business process | The receiving workflow must support multiple deliveries | Update the proposed process map |
| Business requirements | Receipt requirements may need clarification | Review and update BR-002 and BR-003 |
| User stories | Acceptance criteria must cover partial deliveries | Update the relevant user story |
| UAT testing | Existing tests may not cover repeated receipts | Add partial and final delivery test scenarios |
| Reporting | Outstanding quantities must remain visible | Review purchase order and delivery reporting requirements |
| Stakeholders | Warehouse, Procurement and Finance may be affected | Validate the change with each team |
| Data and controls | Receipt quantities must be recorded accurately | Confirm validation and audit requirements |
| Delivery effort | Additional analysis, configuration or testing may be required | Ask the delivery team to estimate the impact |

## 4. Risks and Dependencies

- Incorrect receipt quantities could lead to inaccurate inventory records.
- The system may show misleading order status if partial deliveries are not handled correctly.
- Invoice matching may be affected by differences between ordered, received and invoiced quantities.
- Reporting may be unreliable if outstanding quantities are not calculated consistently.
- The proposed change must be assessed against existing system configuration and business rules.

## 5. Acceptance Criteria to Review

The following criteria are proposed examples and require stakeholder validation.

**Scenario 1: First partial delivery**

Given a purchase order is for 100 units, when the warehouse records receipt of 80 units, then the recorded receipt quantity should be 80 and the remaining quantity should be 20, subject to the agreed business rules.

**Scenario 2: Final delivery**

Given 80 units have already been recorded as received, when the remaining 20 units arrive and are recorded, then the cumulative received quantity should be 100 and the order status should reflect the agreed completion rules.

**Scenario 3: Invalid receipt quantity**

Given a purchase order has an outstanding quantity of 20 units, when a user attempts to record an invalid quantity, then the system should apply the agreed validation and exception handling rules.

## 6. Change Approval Process

1. Record the change request and its business justification.
2. Clarify the expected outcome with the requester.
3. Assess impacts on scope, requirements, processes, data, testing, reporting, risks and delivery effort.
4. Consult affected stakeholders and the IT / ERP team.
5. Present the impact assessment to the authorised decision maker.
6. Record the approval, rejection or deferral.
7. Update the relevant documents and traceability links if approved.
8. Communicate the decision and verify the change during testing.

## 7. Traceability and Documentation

If the change is approved, the Business Analyst should review the relevant business requirements, user stories, process maps, acceptance criteria, UAT test cases and traceability matrix.

Document versions and decisions should be maintained so that the team can identify what changed, why it changed and which deliverables need updating.

## 8. Conclusion

Change impact analysis reduces the risk of implementing a requirement without understanding its wider consequences. It supports informed decisions, controlled scope changes and consistent documentation throughout the project lifecycle.

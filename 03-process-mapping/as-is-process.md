# As-Is Process: Procurement and Goods Receipt

## 1. Purpose

This document describes the current purchasing and goods receipt process for the fictional manufacturing company used in this case study.

## 2. Process Participants

- Procurement team
- Supplier
- Warehouse team
- Finance team

## 3. Current Process

1. The procurement team identifies the need for materials.
2. A purchase order is created and sent to the supplier.
3. The supplier dispatches the materials.
4. The warehouse team receives and checks the delivery.
5. The received quantity is recorded.
6. The finance team receives the supplier invoice.
7. The invoice quantity and amount are checked against the purchase order and goods receipt.
8. Any discrepancies are investigated before the invoice is approved for payment.

## 4. Identified Process Challenges

The following are assumed problems for this fictional scenario:

- Purchase order status is not always visible to the warehouse team.
- Partial deliveries may not be communicated promptly.
- Differences between ordered and received quantities can require manual investigation.
- Supplier invoice discrepancies can delay approval.
- Teams may use inconsistent information when reporting order status.

## 5. Business Analyst Observations

The Business Analyst should investigate how purchase order information is shared, how goods receipts are recorded, how discrepancies are resolved and which controls are required before invoice approval.

These observations are hypotheses for the case study and should be validated with stakeholders in a real project.

## 6. Questions for Stakeholders

- How does the warehouse team know which deliveries are expected?
- How are partial deliveries recorded?
- Who investigates quantity discrepancies?
- How are supplier invoices matched to purchase orders and goods receipts?
- How are unresolved exceptions reported to management?

## 7. Expected Outcome

Documenting the current process provides a baseline for identifying gaps and designing an improved future process.


flowchart TD
    A[Identify material requirement] --> B[Create purchase order]
    B --> C[Send order to supplier]
    C --> D[Supplier dispatches goods]
    D --> E[Warehouse receives delivery]
    E --> F[Record received quantity]
    F --> G[Finance receives supplier invoice]
    G --> H[Compare order, receipt and invoice]
    H --> I{Discrepancy found?}
    I -->|Yes| J[Investigate discrepancy]
    J --> K[Resolve before approval]
    I -->|No| L[Approve invoice according to policy]
    K --> L

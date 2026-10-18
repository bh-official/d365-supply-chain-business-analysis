# Gap Analysis: Supply Chain Process Improvement

## 1. Purpose

This document compares the current and proposed procurement, inventory and supplier invoice processes for a fictional manufacturing company.

The objective is to identify process gaps, assess their business impact and recommend improvements that could be supported by Microsoft Dynamics 365 Finance & Operations.

## 2. Gap Analysis

| Area | Current State | Desired State | Identified Gap | Recommendation |
|---|---|---|---|---|
| Purchase order visibility | Order status is not consistently visible across teams | Authorised users can access reliable order status information | Limited shared visibility | Review purchasing workflows and reporting requirements |
| Goods receipt | Partial deliveries can be difficult to track | Actual quantities are recorded against purchase orders | Inconsistent recording and follow-up | Define goods receipt procedures and validation requirements |
| Inventory accuracy | System records may differ from physical stock | Stock records are accurate and discrepancies are investigated | Weak reconciliation and exception handling | Establish inventory controls and discrepancy reporting |
| Invoice matching | Quantity differences may require manual investigation | Invoices are checked against orders and receipts using agreed rules | Inconsistent matching and escalation | Define invoice matching tolerances and exception workflows |
| Delivery monitoring | Overdue deliveries may not be identified promptly | Overdue orders and deliveries are visible to responsible teams | Limited exception reporting | Define overdue delivery indicators and escalation responsibilities |
| Management reporting | Operational information may be fragmented | Managers can monitor agreed supply chain KPIs | Inconsistent reporting and measures | Establish KPI definitions, data ownership and reporting requirements |

## 3. Root Cause Hypotheses

The following are potential causes to investigate, not confirmed findings:

- Inconsistent processes between departments.
- Incomplete or inaccurate transaction data.
- Unclear ownership of exceptions.
- Limited reporting and alerting.
- Insufficient user training or process documentation.

The Business Analyst should validate these hypotheses through stakeholder interviews, process observation and data analysis.

## 4. Prioritised Recommendations

### Priority 1: Improve Goods Receipt and Inventory Accuracy

Define standard procedures for recording receipts, partial deliveries and stock discrepancies.

**Expected benefit:** More reliable stock information and better purchasing visibility.

### Priority 2: Strengthen Supplier Invoice Matching

Agree matching rules and tolerances with finance stakeholders, including how exceptions should be investigated and approved.

**Expected benefit:** Better financial controls and fewer avoidable payment errors.

### Priority 3: Improve Purchase Order and Delivery Visibility

Define reporting requirements for open orders, expected deliveries and overdue items.

**Expected benefit:** Earlier intervention when supply chain delays occur.

### Priority 4: Standardise Management Reporting

Agree KPI definitions, reporting frequency, data sources and responsibility for reviewing exceptions.

**Expected benefit:** More consistent operational decisions.

## 5. Potential Dynamics 365 Capabilities

The proposed improvements could involve purchase order management, product receipt recording, inventory management, vendor invoice matching and operational reporting in Dynamics 365.

The suitability of each capability must be confirmed through requirements analysis and solution assessment. Configuration, integrations and custom development should not be assumed necessary until the gaps have been validated.

## 6. Risks and Dependencies

- Inaccurate master data could undermine reporting.
- Unclear business rules could lead to inconsistent invoice handling.
- Changes to processes may require user training.
- Reporting quality depends on reliable source data.
- Stakeholders must agree on priorities, controls and success measures.

## 7. Measures of Success

Establish a baseline and agree targets for:

- Inventory record accuracy.
- Goods receipt processing time.
- Supplier invoice discrepancy rate.
- Average exception resolution time.
- On-time delivery rate.

## 8. Conclusion

The analysis suggests that improving transaction visibility, inventory controls, invoice matching and exception reporting could address the stated business problems.

These recommendations remain proposals until validated with stakeholders and assessed against the organisation's requirements.

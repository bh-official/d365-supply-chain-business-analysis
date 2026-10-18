# MoSCoW Prioritisation: Supply Chain Requirements

## 1. Purpose

MoSCoW is a requirements prioritisation technique used by Business Analysts to help stakeholders agree which requirements are essential for a successful delivery and which can be deferred.

The four categories are Must Have, Should Have, Could Have and Won't Have for this delivery.

## 2. Prioritisation Categories

| Category | Meaning | Example |
|---|---|---|
| Must Have | Essential for the solution to meet its core objectives | Recording actual goods received against purchase orders |
| Should Have | Important, but the solution can still operate without it temporarily | Reporting on supplier invoice discrepancies |
| Could Have | Desirable improvement with lower priority | Additional dashboard visualisations |
| Won't Have for This Delivery | Explicitly excluded from the current delivery, but potentially considered later | Advanced predictive supplier analytics |

## 3. Prioritisation Matrix

The following priorities are proposed examples. Final priorities must be agreed with business stakeholders.

| Requirement ID | Requirement | Priority | Rationale |
|---|---|---|---|
| BR-002 | Record goods receipts against purchase orders | Must Have | Accurate receipt records support inventory control and invoice checks |
| BR-003 | Update inventory records following goods receipt | Must Have | Reliable stock records are essential for operations |
| BR-004 | Check supplier invoices against relevant records | Must Have | Supports invoice accuracy and financial controls |
| BR-001 | Provide visibility of purchase order status | Should Have | Improves coordination and reduces manual enquiries |
| BR-005 | Identify and manage discrepancies | Should Have | Supports timely investigation and resolution of exceptions |
| BR-006 | Provide supply chain performance reporting | Should Have | Helps managers monitor operational performance |
| NFR-001 | Apply appropriate access controls | Must Have | Helps protect sensitive business information |
| NFR-002 | Maintain appropriate auditability | Must Have | Supports accountability and investigation of changes |
| NFR-003 | Maintain agreed data quality standards | Must Have | Reliable data is necessary for trustworthy transactions and reporting |
| FUT-001 | Introduce advanced predictive supplier analytics | Won't Have for This Delivery | Requires separate assessment and prioritisation |

## 4. Prioritisation Approach

The Business Analyst should first explain the business problem and the consequences of not delivering each requirement.

Stakeholders should then assess business value, operational risk, compliance obligations, dependencies and delivery effort. The group should agree the priority rather than allowing the Business Analyst to assign priorities without consultation.

Requirements that are mandatory for legal, regulatory, security or financial control reasons need appropriate specialist review before their priority is agreed.

## 5. Example Scenario

The Procurement Manager requests an advanced supplier dashboard, while the Warehouse Manager needs reliable recording of partial deliveries.

The Business Analyst should facilitate a discussion about business impact, risk and dependencies. The group may prioritise partial delivery recording because inaccurate receipt data could affect stock availability and invoice matching, while deferring the advanced dashboard.

The decision and its rationale should be documented for stakeholder approval.

## 6. Dependencies and Risks

- Some requirements depend on other requirements being delivered first.
- Security and financial controls must not be treated as optional merely to save time.
- Stakeholders may disagree about business priorities.
- A requirement's priority may change when new information becomes available.
- Deferred requirements should be recorded so that they are not lost.

## 7. Business Analyst Responsibilities

The Business Analyst facilitates prioritisation discussions, explains the impact of requirements, documents decisions and maintains traceability between requirements, business objectives and acceptance criteria.

The analyst should revisit priorities when the scope, risks, dependencies or business needs change.

## 8. Conclusion

MoSCoW provides a structured way to agree delivery priorities and manage scope. It helps stakeholders focus on essential business outcomes while making informed decisions about improvements that can be delivered later.

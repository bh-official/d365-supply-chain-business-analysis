# Business Requirements Document (BRD)

## Project

Supply Chain Process Improvement using Microsoft Dynamics 365 Finance & Operations concepts

## 1. Purpose

This document defines the business requirements for improving procurement, goods receipt, inventory visibility and supplier invoice matching in a fictional manufacturing company.

## 2. Business Objectives

- Improve visibility of purchase orders and expected deliveries.
- Record goods received accurately.
- Reduce manual investigation of supplier invoice discrepancies.
- Strengthen operational and financial controls.
- Improve supply chain reporting.

## 3. Functional Business Requirements

### BR-001: Purchase Order Visibility

The business must be able to view purchase orders and their current processing status.

Priority: High

Business value: Helps procurement and warehouse teams coordinate expected deliveries.

### BR-002: Goods Receipt Recording

The business must record the actual quantities received against the relevant purchase order.

Priority: High

Business value: Improves stock accuracy and identifies partial deliveries.

### BR-003: Inventory Updates

The business must maintain inventory records in accordance with approved goods receipt and inventory processes.

Priority: High

Business value: Improves visibility of available stock.

### BR-004: Supplier Invoice Matching

The business must be able to compare supplier invoice information against the purchase order and recorded goods receipt.

Priority: High

Business value: Helps identify discrepancies before invoice approval.

### BR-005: Exception Management

The business must provide a way to identify, investigate and resolve discrepancies.

Priority: High

Business value: Reduces unresolved exceptions and supports accountability.

### BR-006: Supply Chain Reporting

The business must be able to report on open purchase orders, outstanding deliveries and unresolved invoice discrepancies.

Priority: Medium

Business value: Supports operational decision-making.

## 4. Non-Functional Requirements

### NFR-001: Access Control

Users must access and perform activities according to their assigned permissions.

### NFR-002: Auditability

Relevant transactions and changes must be traceable in accordance with business and compliance requirements.

### NFR-003: Data Quality

Required purchasing, product, supplier and receipt data must be validated to support accurate processing.

## 5. Assumptions

- The company uses an ERP system to support purchasing, inventory and finance processes.
- Authorised users are responsible for recording and reviewing transactions.
- Invoice matching tolerances and approval rules will be agreed with finance stakeholders.
- The proposed requirements require stakeholder validation.

## 6. Out of Scope

- Actual Dynamics 365 configuration.
- Production deployment and live integrations.
- Changes to real supplier payment arrangements.

## 7. Acceptance and Approval

The requirements must be reviewed by relevant business stakeholders and approved before solution design and user acceptance testing proceed.

## 8. Traceability

Each approved requirement should be linked to its associated user story, acceptance criteria, test case and final test result.

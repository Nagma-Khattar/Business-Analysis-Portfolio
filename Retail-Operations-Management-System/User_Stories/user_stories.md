# User Stories and Acceptance Criteria

## Retail Operations Management System (ROMS)

**Client:** NorthStar Retail Inc.  
**Document Type:** Agile User Stories  
**Prepared By:** Nagma Khattar  

---

# 1. Introduction

This document defines Agile user stories and acceptance criteria for the Retail Operations Management System (ROMS).

User stories describe system functionality from the perspective of different users and stakeholders.

---

# Epic 1: User Management

## US-001: User Login

### User Story

As a registered user, I want to securely log into the system so that I can access authorized features.

### Priority

High

### Acceptance Criteria

Given that the user has valid credentials:

- User can enter username and password.
- System validates credentials.
- User is redirected to the appropriate dashboard.

Given that credentials are invalid:

- System displays an error message.
- User cannot access the system.

---

# Epic 2: Inventory Management

## US-002: Add New Product

### User Story

As an Inventory Manager, I want to add new products so that inventory records remain updated.

### Priority

High

### Acceptance Criteria

- User can enter product information.
- Product ID must be unique.
- Required fields must be completed.
- Product is saved successfully.

---

## US-003: View Inventory

### User Story

As an Inventory Manager, I want to view available inventory so that I can monitor stock levels.

### Priority

High

### Acceptance Criteria

- User can search products.
- System displays product details.
- Current quantity is displayed.
- Low-stock products are identified.

---

## US-004: Update Inventory

### User Story

As an Inventory Manager, I want to update stock information so that inventory records remain accurate.

### Priority

High

### Acceptance Criteria

- Authorized users can modify inventory.
- Changes are saved.
- Updated quantity is displayed.

---

# Epic 3: Sales Management

## US-005: Record Customer Purchase

### User Story

As a Sales Associate, I want to record customer purchases so that sales transactions are accurately maintained.

### Priority

High

### Acceptance Criteria

- User can select products.
- Quantity is recorded.
- Total amount is calculated.
- Inventory is updated automatically.

---

## US-006: View Sales Reports

### User Story

As a Store Manager, I want to view sales reports so that I can analyze business performance.

### Priority

Medium

### Acceptance Criteria

- User can select reporting period.
- System generates sales summary.
- Report displays sales information.

---

# Epic 4: Customer Management

## US-007: Create Customer Profile

### User Story

As a Customer Service Representative, I want to create customer profiles so that customer information can be maintained.

### Priority

Medium

### Acceptance Criteria

- User can enter customer details.
- Customer record is stored.
- Customer ID is generated.

---

# Epic 5: Reporting and Analytics

## US-008: Generate Business Reports

### User Story

As an Executive Manager, I want business reports so that I can make informed decisions.

### Priority

High

### Acceptance Criteria

- User can request reports.
- System generates accurate information.
- Reports can be viewed and exported.

---

# User Story Summary

| ID | User Story | Priority |
|---|---|---|
| US-001 | User Login | High |
| US-002 | Add Product | High |
| US-003 | View Inventory | High |
| US-004 | Update Inventory | High |
| US-005 | Record Sales | High |
| US-006 | Sales Reports | Medium |
| US-007 | Customer Profile | Medium |
| US-008 | Business Reports | High |

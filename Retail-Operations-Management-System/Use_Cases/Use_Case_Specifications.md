# Use Case Specifications

## Retail Operations Management System (ROMS)

**Client:** NorthStar Retail Inc.  
**Document Type:** Use Case Specifications  
**Prepared By:** Nagma   

---

# 1. Introduction

This document describes the detailed use case specifications for the Retail Operations Management System (ROMS). Each use case defines how users interact with the system to accomplish specific business goals.

---

# UC-01 User Login

## Primary Actor

Registered User

## Goal

Allow authorized users to securely access the system.

## Preconditions

- User is registered.
- User account is active.

## Trigger

User selects the **Login** option.

## Main Success Scenario

1. User enters username and password.
2. System validates credentials.
3. System authenticates the user.
4. User is redirected to the appropriate dashboard.

## Alternate Flow

**Invalid Credentials**

1. System displays an error message.
2. User is prompted to retry.

## Postconditions

- User session is established.
- User gains access based on assigned role.

---

# UC-02 Add New Product

## Primary Actor

Inventory Manager

## Goal

Add a new product to the inventory.

## Preconditions

- User is authenticated.
- Inventory Manager has appropriate permissions.

## Trigger

Inventory Manager selects **Add New Product**.

## Main Success Scenario

1. Enter product details.
2. System validates required information.
3. Product is saved.
4. Inventory database is updated.
5. Confirmation message is displayed.

## Alternate Flow

- Missing required information.
- Duplicate Product ID.

## Postconditions

New product becomes available in inventory.

---

# UC-03 View Inventory

## Primary Actor

Inventory Manager, Sales Associate, Store Manager

## Goal

View current inventory information.

## Preconditions

- User is authenticated.

## Trigger

User selects **View Inventory**.

## Main Success Scenario

1. System retrieves inventory records.
2. Products are displayed.
3. User searches or filters inventory if required.

## Alternate Flow

No inventory records found.

## Postconditions

Inventory information is displayed.

---

# UC-04 Update Inventory

## Primary Actor

Inventory Manager

## Goal

Modify inventory quantities or product information.

## Preconditions

- User is authenticated.
- Product exists.

## Trigger

Inventory Manager selects **Update Inventory**.

## Main Success Scenario

1. Search for product.
2. Select product.
3. Modify information.
4. Save changes.
5. System updates inventory.

## Alternate Flow

Product not found.

## Postconditions

Inventory reflects updated information.

---

# UC-05 Record Sales Transaction

## Primary Actor

Sales Associate

## Goal

Record customer purchases.

## Preconditions

- User is authenticated.
- Product exists in inventory.

## Trigger

Sales Associate initiates a sales transaction.

## Main Success Scenario

1. Search products.
2. Select products.
3. Enter quantity.
4. System calculates total.
5. Payment is confirmed.
6. Sale is recorded.
7. Inventory quantity is updated.

## Alternate Flow

- Insufficient inventory.
- Payment failure.

## Postconditions

Sales transaction is successfully recorded.

---

# UC-06 Create Customer Profile

## Primary Actor

Customer Service Representative

## Goal

Create a customer profile.

## Preconditions

- User is authenticated.

## Trigger

Representative selects **Create Customer Profile**.

## Main Success Scenario

1. Enter customer information.
2. Validate required fields.
3. Save customer profile.
4. Confirmation message displayed.

## Alternate Flow

Duplicate customer information.

## Postconditions

Customer profile is stored.

---

# UC-07 View Sales Report

## Primary Actor

Store Manager

## Goal

Review sales performance.

## Preconditions

- User is authenticated.
- Sales data exists.

## Trigger

Manager selects **View Sales Report**.

## Main Success Scenario

1. Select report period.
2. System retrieves sales data.
3. Sales report is displayed.

## Alternate Flow

No sales data available.

## Postconditions

Sales report is available for review.

---

# UC-08 Generate Business Reports

## Primary Actor

Store Manager

## Goal

Generate operational and business reports.

## Preconditions

- User is authenticated.

## Trigger

Manager selects **Generate Business Reports**.

## Main Success Scenario

1. Select report type.
2. Select report criteria.
3. System generates report.
4. Report is displayed.
5. User exports or prints report.

## Alternate Flow

Requested report cannot be generated.

## Postconditions

Business report is successfully generated.

---

# 2. Traceability Matrix

| Use Case | Related User Story |
|-----------|--------------------|
| UC-01 | US-001 User Login |
| UC-02 | US-002 Add New Product |
| UC-03 | US-003 View Inventory |
| UC-04 | US-004 Update Inventory |
| UC-05 | US-005 Record Sales Transaction |
| UC-06 | US-006 Create Customer Profile |
| UC-07 | US-007 View Sales Report |
| UC-08 | US-008 Generate Business Reports |

---

# 3. Conclusion

These use case specifications describe the interactions between users and the Retail Operations Management System. They provide a clear understanding of system functionality and serve as a foundation for system design, testing, and implementation.

---

**End of Document**
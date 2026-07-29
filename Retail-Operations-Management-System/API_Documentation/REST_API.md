# REST API Documentation

## Retail Operations Management System (ROMS)

**Client:** NorthStar Retail Inc.  
**Document Type:** REST API Documentation  
**Prepared By:** Nagma 

---

# Overview

This document provides the functional REST API endpoints required by the Retail Operations Management System (ROMS). These APIs support authentication, inventory management, customer management, sales processing, and reporting.

---

# Authentication

## User Login

| Method | Endpoint |
|----------|-----------|
| POST | /api/login |

### Request

```json
{
  "username": "user@example.com",
  "password": "********"
}
```

### Response

```json
{
  "token": "JWT Token",
  "role": "Inventory Manager"
}
```

---

# Inventory

## Get Products

| Method | Endpoint |
|----------|-----------|
| GET | /api/products |

---

## Add Product

| Method | Endpoint |
|----------|-----------|
| POST | /api/products |

---

## Update Product

| Method | Endpoint |
|----------|-----------|
| PUT | /api/products/{productId} |

---

## Delete Product

| Method | Endpoint |
|----------|-----------|
| DELETE | /api/products/{productId} |

---

# Customers

## Create Customer

| Method | Endpoint |
|----------|-----------|
| POST | /api/customers |

---

## View Customer

| Method | Endpoint |
|----------|-----------|
| GET | /api/customers/{customerId} |

---

# Sales

## Record Sales Transaction

| Method | Endpoint |
|----------|-----------|
| POST | /api/sales |

---

## View Sales History

| Method | Endpoint |
|----------|-----------|
| GET | /api/sales |

---

# Reports

## Sales Report

| Method | Endpoint |
|----------|-----------|
| GET | /api/reports/sales |

---

## Business Report

| Method | Endpoint |
|----------|-----------|
| GET | /api/reports/business |

---

# HTTP Status Codes

| Code | Description |
|------|-------------|
| 200 | Success |
| 201 | Created |
| 400 | Bad Request |
| 401 | Unauthorized |
| 404 | Resource Not Found |
| 500 | Internal Server Error |

---

# Conclusion

These REST APIs provide the functional interface required to support the core features of the Retail Operations Management System.

---

**End of Document**

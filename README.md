# E-Commerce Sales Analysis (SQL)

An SQL querying project 
carried out on a 1,200 row E-Commerce dataset spanning 2023, 
2024 and 2025 as part of my Data Analytics Internship at DecodeLabs.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Tools Used](#tools-used)
- [SQL Analysis](#sql-analysis)
- [Repository Structure](#repository-structure)
- [Author](#author)

## Project Overview

This project was completed as part of a structured Data Analytics 
Internship programme at DecodeLabs. The goal was to explore, 
analyse and extract business insights from an E-Commerce dataset 
using core analyst tool — Microsoft SQL Server.

The project was completed in:
- **Phase 2 (SQL):** Database creation, data importation and 
  business insight extraction using SQL queries

## Dataset Description

| Detail | Information |
|--------|-------------|
| **Source** | DecodeLabs Internship Dataset |
| **Rows** | 1,200 Orders |
| **Columns** | 14 |
| **Time Period** | January 2023 — June 2025 |

### Columns in the Dataset

| Column | Data Type | Description |
|--------|-----------|-------------|
| OrderID | Text | Unique order identifier |
| Date | Date | Date order was placed |
| CustomerID | Text | Unique customer identifier |
| Product | Text | Product purchased |
| Quantity | Integer | Number of units ordered |
| UnitPrice | Decimal | Price per unit |
| ShippingAddress | Text | Customer delivery address |
| PaymentMethod | Text | Method of payment used |
| OrderStatus | Text | Current status of the order |
| TrackingNumber | Text | Shipment tracking reference |
| ItemsInCart | Integer | Number of items in cart |
| CouponCode | Text | Discount coupon applied (NULL if none) |
| ReferralSource | Text | Marketing channel that brought the customer |
| TotalPrice | Decimal | Final order value |

## Tools Used

| Tool | Purpose |
|------|---------|
| MS SQL Server (SSMS) | Database creation and SQL querying |
| GitHub | Version control and portfolio hosting |

## SQL Analysis

### Database Setup
- Database created in MS SQL Server Management Studio (SSMS)
- Dataset imported as a CSV flat file
- Data types correctly assigned to all 14 columns

### Query Categories
QL queries were written and executed across 8 categories:

| Category | Description |
|----------|-------------|
| Basic SELECT | View full and partial dataset |
| WHERE Filtering | Filter by status, year, price, channel |
| ORDER BY | Sort by revenue, date and order value |
| GROUP BY + Aggregations | COUNT, SUM, AVG by product, channel, year |
| HAVING | Filter aggregated results above a threshold |
| CASE WHEN | Handle NULL coupon values and custom grouping |
| Date Functions | YEAR(), MONTH(), DATENAME() for time analysis |
| Business Insight Queries | Top customers, discount impact |

## Repository Structure

```
ecommerce-analysis/
│
├── data/
│   └── ecommerce_dataset.csv
│
├── sql/
│   └── ecommerce_queries.sql
│
└── README.md
```

## Author

**Enimabasi Ukpong**
Data Analytics Intern — DecodeLabs

Connect with me:
- LinkedIn: www.linkedin.com/in/enimabasi-ukpong-98ba5822b
- Twitter/X: https://x.com/enimabasi
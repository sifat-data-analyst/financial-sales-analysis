# Financial Sales Analysis — Data Dictionary

## Dataset Overview

The dataset contains 9,994 sales transaction records and 19 original columns.

Each record represents a sales transaction line associated with an order, customer, product, shipping details, and financial measures.

## 1. Order and Transaction Fields

| Column | Expected Data Type | Description | Business Purpose |
|---|---|---|---|
| Row ID | Integer | Unique row identifier | Record identification |
| Order ID | Text | Identifier assigned to an order | Order tracking and transaction analysis |
| Order Date | Date | Date when the order was placed | Time-based sales analysis |
| Ship Date | Date | Date when the order was shipped | Shipping performance analysis |
| Ship Mode | Text / Category | Shipping service level | Shipping method comparison |

## 2. Customer and Geographic Fields

| Column | Expected Data Type | Description | Business Purpose |
|---|---|---|---|
| Customer ID | Text | Unique customer identifier | Customer-level analysis |
| Segment | Category | Customer segment | Customer segmentation |
| Country | Text | Country associated with the transaction | Geographic analysis |
| City | Text | Customer or delivery city recorded in the dataset | City-level analysis |
| State | Text | State associated with the transaction | State-level analysis |
| Region | Category | Geographic sales region | Regional performance comparison |

## 3. Product Fields

| Column | Expected Data Type | Description | Business Purpose |
|---|---|---|---|
| Product ID | Text | Unique product identifier | Product tracking |
| Category | Category | Main product category | Category-level performance |
| Sub-Category | Category | Product sub-category | Detailed product analysis |
| Product Name | Text | Product description or name | Product-level sales analysis |

## 4. Financial and Quantity Fields

| Column | Expected Data Type | Description | Business Purpose |
|---|---|---|---|
| Sales | Decimal / Currency | Sales amount associated with the transaction line | Revenue analysis |
| Quantity | Integer | Number of units sold | Sales volume analysis |
| Discount | Decimal | Discount rate applied to the transaction line | Discount impact analysis |
| Profit | Decimal / Currency | Profit associated with the transaction line | Profitability analysis |

## 5. Analytical Usage

The dataset supports analysis of:

- Sales and profit performance.
- Order and customer activity.
- Product and category performance.
- Regional and geographic trends.
- Shipping methods.
- Discount and profitability relationships.
- Historical sales trends.

## 6. Data Dictionary Notes

- Expected data types describe the intended analytical meaning of each field; actual Excel cell storage formats may vary.
- Order ID and Customer ID are identifiers, not numerical measures.
- Sales and Profit are financial measures.
- Discount should be interpreted according to its stored scale and format.
- Row ID is a record identifier and should not be treated as a business performance metric.

## 7. Dataset Scope

This dictionary describes the 19 original columns in the RAW DATA worksheet. Additional calculated fields in the CLEAN DATA worksheet are outside this original-field dictionary.

# Financial Sales Analysis — Validation Report

**Validation Date:** November 18, 2026  
**Project:** Financial Sales Analysis  
**Tool:** Microsoft Excel

## 1. Dataset Structure

| Item | Result |
|---|---:|
| Raw Data Rows | 9,994 |
| Raw Data Columns | 19 |
| Clean Data Rows | 9,994 |
| Clean Data Columns | 21 |
| Row Count Match | Passed |

## 2. Data Quality Checks

- No missing values were detected in the audited raw and clean data ranges.
- No complete duplicate rows were detected.
- Order ID unique count: 5,009.
- Customer ID unique count: 793.
- Repeated Order IDs and Customer IDs represent multiple transactions and are not automatically treated as duplicate records.
- 48 differences were identified in Product Name formatting between raw and clean data.
- The other 18 original columns matched during the comparison.

## 3. Formula Validation

The workbook contains formulas across the following worksheets:

| Worksheet | Formula Count |
|---|---:|
| RAW DATA | 0 |
| CLEAN DATA | 19,988 |
| EDA | 11,542 |
| INFO FINDER | 9 |
| PIVOT TABLES | 0 |
| DASHBOARD | 11 |

A broken formula reference was identified and repaired in EDA!AM9998.

The repaired formula was saved and subsequently verified after reopening the repair workbook.

Excel formula-error checks were performed across all six worksheets. No formula errors were found during those checks.

## 4. Dashboard KPI Verification

| KPI | Verified Value |
|---|---:|
| Total Sales | $2,297,200.86 |
| Total Profit | $286,397.02 |
| Total Orders | 5,009 |
| Total Customers | 793 |
| Profit Margin | 12.47% |

The dashboard KPI values were compared with the workbook's Pivot Table results.

## 5. Business Analysis Checks

The following results were verified from the workbook:

- Highest sales region: West.
- Highest profit region: West.
- Highest sales category: Technology.
- Highest profit category: Technology.
- Highest sales year: 2017.
- Highest sales segment: Consumer.

## 6. Interactive Dashboard

The user reported that the dashboard slicers were functioning.

Slicer categories:
- Region
- Category
- Segment
- Ship Mode

A separate visual inspection and screenshot review remain pending.

## 7. Limitations and Pending Verification

- The original dataset source and redistribution license have not yet been identified.
- Public redistribution of the dataset-containing workbook is not approved until licensing permission is confirmed.
- Dashboard visual presentation requires a final screenshot review.
- Additional INFO FINDER test cases have not yet been completed.

## 8. Validation Status

The structural, data-quality, formula, and KPI checks described above have been completed.

This report documents the checks performed and the remaining limitations. It does not establish permission to redistribute the original dataset.

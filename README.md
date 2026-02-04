# Sales-Performance-MIS-Revenue-Diagnostics

## Project Overview
This project demonstrates an end-to-end MIS (Management Information System) workflow using sales transaction data. The objective is to analyze sales performance across executives, regions, and products, identify key revenue drivers, and provide data-backed business recommendations.

The project simulates real-world MIS reporting and analytical practices typically used in sales and operations teams.

---

## Dataset Description
The dataset consists of sales transactions with the following fields:
- Date
- Region
- Executive
- Product
- Quantity
- Revenue

Each row represents an individual sales transaction.  
The data is simulated for portfolio purposes.

---

## Data Cleaning & Validation
The following checks were performed:
- Verified data types for date and numeric fields
- Reviewed duplicate transaction risk using multi-column validation
- Added a `Review_Flag` column to document data quality checks
- Standardized values and ensured no missing records
- Removed timestamps after confirming they were not required for analysis

---

## MIS Summary Reporting
Summary tables were created to analyze performance across key dimensions:
- Executive-wise sales performance
- Region-wise sales performance
- Product-wise sales performance

Each summary includes:
- Total Quantity
- Total Revenue
- Contribution (%) to overall revenue

![MIS Summary Tables](/Sales_Performance_MIS&Revenue_Diagnostics/Images/Clean_data_Summary.png)

---

## Revenue Diagnostics
Revenue diagnostics were performed to understand *why* performance differs.

The analysis focused on:
- Transaction frequency (number of sales records)
- Average quantity per transaction
- Pricing consistency across products

Pivot tables were used to efficiently analyze these metrics.

![Revenue Diagnostics](/Sales_Performance_MIS&Revenue_Diagnostics/Images/Revenue_Diagnostics.png)

---

## Key Insights
- Revenue differences are primarily driven by sales volume (transaction frequency and quantity), not pricing.
- Higher-performing executives show both higher transaction counts and larger average basket sizes.
- Regional revenue variation is linked to sales activity and coverage rather than price differences.
- Shoes contribute a higher share of revenue due to higher unit price and consistent sales volume.

![Insights](/Sales_Performance_MIS&Revenue_Diagnostics/Images/recommendation.png)

---

## Recommendations
- Short-term promotional or bundling strategies can be tested in low-performing regions to increase transaction frequency, subject to margin evaluation.
- Best practices from high-performing executives can be reviewed and replicated across regions.
- Since revenue is volume-driven, efforts should focus on increasing sales activity and average basket size rather than price adjustments.

---

## Tools Used
- Microsoft Excel
  - Tables
  - Pivot Tables
  - Data Validation
  - Structured formulas

---

## 📎 Files Included
- `analysis/Sales_Performance_MIS_Revenue_Diagnostics.xlsx`
- Supporting screenshots for documentation

---

## Note
This project is designed to reflect practical MIS and analytical thinking rather than tool-heavy automation. All insights and recommendations are strictly data-backed.

# E-commerce Sales Performance Analysis Using Excel

## Project Overview

This project analyzes fictional e-commerce sales data for Q1 2026 using Microsoft Excel and Power Query. The objective was to examine recorded revenue and profit, compare product and regional performance, identify monthly revenue trends, and flag data-quality issues requiring further investigation.

An interactive Excel dashboard was developed to present the findings and help readers explore performance across products, categories, and regions.

## Business Questions

This analysis aimed to answer the following questions:

1. What were the total recorded revenue and profit during Q1 2026?
2. What was the overall profit margin?
3. Which products contributed the most to recorded revenue and profit?
4. Which regions contributed the most to recorded revenue, and which had the highest profit margin?
5. How did revenue change from January through March?
6. What data-quality issues required further investigation?

## Tools Used

* **Microsoft Excel:** Formulas, PivotTables, PivotCharts, and dashboard development.
* **Power Query:** Data cleaning and transformation.
* **Excel slicers:** Interactive filtering by product, category, and region.

## Data Cleaning and Preparation

The following preparation steps were performed:

* Profiled the dataset to understand its structure and data quality.
* Standardized inconsistent product names and region labels.
* Removed the confirmed duplicate transaction associated with Order ID 8005.
* Checked the dataset for missing values.
* Identified a negative quantity in Order ID 8010 and flagged it for further investigation rather than automatically deleting or modifying the transaction.

The negative quantity remains unresolved. Therefore, the reported metrics should be treated as provisional until the transaction is validated.

## Key Performance Indicators

| Metric                  |     Result |
| ----------------------- | ---------: |
| Total recorded revenue  | ₦3,820,000 |
| Total recorded profit   |   ₦603,000 |
| Overall profit margin   |     15.79% |
| Number of unique orders |         14 |

## Key Findings

### Product Performance

Laptop generated the highest recorded revenue of ₦1,500,000, representing approximately 39.3% of total recorded revenue. It also generated the highest recorded product profit of ₦210,000.

Phone recorded a higher profit margin than Laptop: approximately 16.7% compared with 14.0%.

### Regional Performance

Lagos generated ₦2,430,000 in recorded revenue, representing approximately 63.6% of the total. It also recorded the highest regional profit at ₦355,000.

Abuja recorded the highest regional profit margin at approximately 18.4%, compared with 14.6% in Lagos and 16.7% in Port Harcourt.

### Monthly Revenue Trend

Recorded revenue declined from ₦1,300,000 in January to ₦830,000 in February, before increasing to ₦1,690,000 in March.

March recorded the highest monthly revenue. The increase between February and March was approximately 103.6%.

Further investigation would be needed to determine the factors behind this increase and whether the performance could be sustained.

## Recommendations

1. Investigate the factors contributing to Laptop revenue and profit, including regional demand, pricing, and order patterns.
2. Examine why Abuja recorded a higher profit margin than the other regions and whether the factors involved could be replicated elsewhere.
3. Investigate the factors behind March's revenue increase and assess whether the trend can be sustained.
4. Validate the negative quantity recorded in Order ID 8010 before treating the reported metrics as final.

## Limitations

* The dataset is fictional and was created for learning and portfolio purposes.
* The negative quantity in Order ID 8010 remains unresolved.
* The dataset does not contain sufficient information to establish the causes of monthly revenue changes or regional margin differences.

These limitations should be considered when interpreting the results.

## Dashboard Preview

![Q1 2026 Sales Dashboard](images/Q1_2026_Sales_Dashboard.png)

## Project Deliverables

* Excel workbook containing the sales analysis and interactive dashboard.
* Dashboard screenshot for a quick visual overview.
* Project documentation describing the analysis, findings, and limitations.

## Conclusion

This project demonstrates the use of Excel and Power Query to prepare sales data, analyze business performance, identify trends, and communicate findings through an interactive dashboard. It also demonstrates the importance of documenting data-quality issues and avoiding unsupported conclusions.

*This is a learning project based on fictional data and does not represent the performance of a real business.*

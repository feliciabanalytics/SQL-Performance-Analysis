# AdventureWorks Data Exploration

## Project Overview
This exploratory project leverages the **AdventureWorks** dataset. By analyzing sales, product, and geographic data this project identifies regional performance outliers and operational trends. 

## The Data 
* Product Lookup.csv - Product details including: unique product idenitifier, product and model name, product cost, product price, product sku, and product description
* Territory Lookup.csv - Territory details including: sales territory identifier, region, country, and continent
* Sales Data 2021.csv - Sales data including: line item order quantity, customer identified, terriority identifier, product identifier, order number, and  order dates

Note: All data represents synthetically generated values for fictional company "AdventureWorks". Sales data assumes currency standardization. Transation values are preconverted to functional currency (USD). Further analysis would be needed to understand the impact of real-world currency fluctuations. This analysis focuses on gross revenue performance

## Business Questions Explored
1.  In which regions are we seeing the highest average cart size? Which countries have the highest items per order on average?
2.  How are the countries performing agains the average? Which regions have lower sales compared to the global average?

## Key Insights

### Revenue Performance
* **Global Average Revenue:** $389.56 per line item
* **High Performing Markets:** Australia leads maintaining a 1.41 performance ratio (performing 41% above global average). Germany follows with 1.17 performance ratio
* **Underperforming Markets:** Cananda (0.45 performance ratio) and the United States (0.83 performance ratio are currently trailing
  
### Units per Transaction
* AdventureWorks maintains a global average of 2 units per order
* **Top Performer:** The United Kingdom leads with an average of 2.35 items per order, suggested higher cart purchasing trends
  
## Demonstrated Skills
* **Business Acumen**: Providing actionable analysis to stakeholder questions
* **KPIs & Operational Metrics**:
* **SQL Profiency**: Complex queries, table joins, aggregations, window functions

## SQL Functions & Analytical Concepts
* Data Normalization
* Aggregrate Functions
* Window Functions
* Performance Ratio Calculations
* Common Table Expressions (CTEs)
* Table Joins
* Subqueries
* Aliases

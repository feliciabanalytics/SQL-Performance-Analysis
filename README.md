# AdventureWorks Data Exploration

## The Data 
* Product Lookup.csv - Product details including: unique product idenitifier, product and model name, product cost, product price, product sku, and product description
* Territory Lookup.csv - Territory details including: sales territory identifier, region, country, and continent
* Sales Data 2021.csv - Sales data including: line item order quantity, customer identified, terriority identifier, product identifier, order number, and  order date
Note:  Sales data assumes currency standardization. Transation values are preconverted to functional currency (USD). Further analysis would be needed to isolate the impact of currency fluctuations. This analysis focuses on gross revenue performance

Note: All data represents synthetically generated values for fictional company "AdventureWorks"

## Business Questions Explored
1.  In which regions are we seeing the highest average cart size? Which countries have the highest items per order on average?
2.  How are the countries performing agains the average? Which regions have lower sales compared to the global average?

## Key Insights

### Geographic 
* AdventureWorks generates $390 of sales revenue on average across all regions, with an average of 2 units per sale across all regions
* **Leading Region in Cart Size**: United Kingdom (2.35 Items per Order) 
* **Top 2 Highest Sales Regions**: Australia (41% better than average) and Germany (17% better than average)
* **Bottom 2 Highest Sales Regions**: Canada (55% worse than average) and United (17% worse than average)
  
## Demonstrated Skills
* **Business Acumen**: Providing actionable analysis to stakeholder questions
* **SQL Profiency**: Complex queries, table joins, aggregations, window functions

## SQL Functions & Analytical Concepts
* Aggregrate Functions
* Window Functions
* Performance Ratio Calculations
* Common Table Expressions (CTEs)
* Table Joins

# DSA-SQL-Project
## Project Title: Kultra Mega Stores Inventory Analysis Report

### Project Overview
This project involved a comprehensive analysis of order data from Kultra Mega Stores (KMS) Abuja division, spanning from 2009 to 2012. The primary objective was to use SQL skills to extract key insights regarding sales, costs, and customer behavior to inform management decisions.

### Data Source
The analysis was conducted using the KMS Sql Case Study.csv file. This dataset contains detailed order information, including product categories, sales figures, customer demographics, shipping methods, and order priorities, for the specified period of 2009 to 2012.

### Tools Used
-	SQL: For all data extraction, transformation, and analytical querying.
-	SQL Server Management Studio (SSMS): The integrated environment used for connecting to SQL Server, importing the CSV data, and executing SQL queries.
-	Microsoft Excel: Used for initial inspection of the CSV file.

### Data Cleaning and Preparation
The KMS Sql Case Study.csv file was imported into a SQL Server database (e.g., KMS_Sales_DB) using the SSMS Import Flat File. During this process, column mappings and data types were carefully looked into and adjusted to ensure accurate representation within the SQL Server table. 

This also included verifying correct data types for dates (Order Date), numeric values (Sales, Profit, Shipping Cost, Discount), and text fields (Customer Name, Category, Ship Mode, Returns).

### Exploratory Data Analysis (EDA)
The EDA phase involved executing a series of SQL queries designed to answer specific questions across two case scenarios: General Sales and Cost Analysis, and Customer and Order Behavior. These queries utilized aggregation functions (SUM, COUNT, AVG), filtering (WHERE clauses), grouping (GROUP BY), and ordering (ORDER BY) to derive meaningful data and identify trends within the dataset.

### Data Analysis 
The following findings were derived from the SQL queries executed against the KMS order data:
#### Case Scenario I: General Sales and Cost Analysis

1. Product Category with Highest Sales:
	The product category with the highest sales was Technology with a total sale of $5,984,248.17.

2. Top 3 and Bottom 3 Regions in Terms of Sales:
  - Top 3 Regions:
    
    a. West: $3,597,549.26
    b. Ontario: $3,063,212.47
    c. Prarie: $2,837,304.61
  - Bottom 3 Regions:
    
    a. Nunavut: $116,376.48
    b. Northwest Territories: $800,847.33
    c. Yukon: $975,867.38
    
3. Total Sales of Appliances in Ontario:
The total sales of appliances in Ontario amounted to $202,346.84.
4. Bottom 10 Customers by Revenue:
The bottom 10 customers based on their total sales were:
  - Jeremy Farry: $85.72
  - Natalie DeCherney: $125.90
  - Nicole Fjeld: $153.03
  - Katrina Edelman: $180.76
  - Dorothy Dickinson: $198.08
  - Christine Kargatis: $293.22
  - Eric Murdock: $343.33
  - Chris McAfee: $350.18
  - Rick Huthwaite: $415.82
  - Mark Hamilton: $450.99
5. Shipping Method with Most Incurred Shipping Cost:
KMS incurred the most shipping cost using the Delivery Truck method, with a total cost of $51,971.94.

#### Case Scenario II: Customer and Order Behavior
6. Most Valuable Customers and Their Typical Purchases:
The most valuable customers were identified as:
  - Emily Phan: Total Sales: $117,124.44 - Typically purchased: Office Supplies, Technology, Furniture.
  - Deborah Brumfield: Total Sales: $97,433.13 - Typically purchased: Technology, Furniture, Office Supplies.
  - Roy Skaria: Total Sales: $92,542.15 - Typically purchased: Office Supplies, Furniture, Technology.
  - Sylvia Foulston: Total Sales: $88,875.76 - Typically purchased: Furniture, Office Supplies, Technology.
  - Grant Carroll: Total Sales: $88,417.00 - Typically purchased: Office Supplies, Technology, Furniture.
7. Small Business Customer with Highest Sales:
The small business (retail) customer with the highest sales was Dennis Kane with total sales of $75,967.59.
8. Corporate Customer with Most Orders (2009-2012):
The Corporate Customer (Wholesales) who placed the most orders between 2009 and 2012 was Adam Hart with 18 distinct orders.
9. Most Profitable Consumer Customer:
The most profitable consumer customer was Emily Phan with a total profit of $34,005.44.
10. Customers Who Returned Items and Their Segments:
Customers who returned items and their respective segments include:



11. Appropriateness of Shipping Cost Spending Based on Order Priority:
  - Analysis of Shipping Method Costs: Based on the data, 'Delivery Truck' was the most expensive shipping method with an average cost of $45.35, while 'Regular Air' was the most economical with an average cost of $7.66. 'Express Air' fell in between....


### Recommendation
Based on the key findings, it is recommended that KMS management:
1. Capitalize on Top-Performing Categories: Invest further in the highest-selling product categories (e.g., Technology) to maximize revenue and market share.
2. Target Bottom Customers: Implement specific strategies (e.g., personalized promotions, loyalty programs, direct outreach) to re-engage and increase revenue from the identified bottom 10 customers.
3. Optimize Shipping Logistics: Continuously monitor the allocation of shipping methods based on order priority. Ensure that faster, more expensive methods are reserved for truly urgent orders, and economical methods are consistently utilized for less time-sensitive deliveries to optimize shipping costs.
4. Customer Segmentation Focus: Deep insights into valuable customers (e.g., corporate, small business, consumer) to tailor product offerings, marketing campaigns, and service levels to each segment's specific needs and purchasing behaviors.
5. Address Returns: Investigate the reasons behind returns from identified customers and segments to reduce future occurrences and improve customer satisfaction.

### Limitation
This analysis is based solely on the provided KMS Sql Case Study.csv dataset, covering orders from 2009 to 2012 for the Abuja division. It does not include external market data, competitor analysis, or more recent sales trends. The insights are limited to the available columns and the specific questions posed. Further analysis containing additional data sources and a broader time frame could provide a wholesome understanding of KMS's overall performance.

### Queries Used



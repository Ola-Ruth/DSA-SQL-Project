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
    
3.	Total Sales of Appliances in Ontario:
The total sales of appliances in Ontario amounted to $202,346.84.
4.	Bottom 10 Customers by Revenue:
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
5.	Shipping Method with Most Incurred Shipping Cost:
KMS incurred the most shipping cost using the Delivery Truck method, with a total cost of $51,971.94.


Process Workflow
1. Data Loading
Loaded CSV files using PySpark
Used header option to read column names
2. Data Cleaning
Removed null values using dropna()
Converted total_amount to integer type for calculations
3. Data Processing & Analysis
## I tried to solve different queries like
  1. Daily Sales
     
Calculated total sales for each day
Helps in understanding daily business performance
 2. City-wise Revenue
 
Joined sales and customer data
Calculated revenue for each city
Helps identify high-performing locations
 3. Repeat Customers
 
Found customers who made more than 2 purchases
Helps identify loyal customers
 4. Highest Spending Customer per City
 
Calculated total spend per customer
Identified top customer in each city
 Useful for targeted marketing
 5. Final Reporting Table
 
Created a summary table with:
Customer ID
Name
City
Total Spend
Order Count



Key Learnings

Through this phase, I learned:

How to use PySpark DataFrames
Performing joins and aggregations
Handling real-world data cleaning
Writing efficient transformations

# Sales-Insights
Data Analytics project-Sales Insight

A all-round data analytics project all the way from ETL to visualized report making with all and unusually possible problems tackled using PowerBI and MySQL

Transformations done:
  1. Currency conversion (USD to INR value) for aggregation operations
  2. Elimination of currency duplication (two INR distinct currency found during search, they are "INR" and "INR#(cr)", of which "INR" are duplicate values)
  3. Removal of Sales amount that is -1 and 0 in value.
  4. Removal of market codes that has blank values (there happened two sale in Paris and France which is not a permanent outlet)
  5. New aggregated column for Normalized date and sales_amount.
  6. Relations established to two tables( sales,date and sales,market) to maintain a star schema relational database

Report:
  1. Need to know the total revenue and quatities sold
  2. Find which market place brings high revenue and sales made
  3. Figure the top 5 products and customers
  4. Analyse the trend of business progress

what more insights can be done:
  1. Find total profit margin, and region wise
  2. Figure the products least performing and products with high production costs
  3. Figure the trend of business on high performing products to manage the production rate
  4. Figure the products that delined in trend over years for feedback to improvise.
  


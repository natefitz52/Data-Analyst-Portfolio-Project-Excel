# Project Overview
This project explores sales data from a coffee shop chain, aiming to uncover trends in monthly revenue and product performance. By examining individual transactions, the analysis identifies customer preferences, sales patterns, and differences in performance across various store locations. The goal is to derive insights that can inform decisions on product offerings, promotional strategies, and store management to boost overall sales.

Repository Contents
data/: Contains the main dataset, which includes transaction details and a summary of monthly revenues.

Coffee Shop Sales.xlsx: The original data file with two sheets: one for monthly revenue summaries and one for detailed transaction data.
notebooks/: Jupyter notebooks that document each step of the analysis.

data_cleaning.ipynb: Details the process used to clean and prepare the data, handling issues like missing values and inconsistent formatting.
analysis.ipynb: Contains the core analysis, where we examine trends in product sales, customer behavior, and store performance.
visualizations/: Visual summaries of the findings, including graphs of revenue trends and product category performance.

monthly_revenue_trends.png: A visual representation of the coffee shop's revenue patterns over the months.
product_sales_by_category.png: A chart showing which product categories drive the most sales.
README.md: This file, providing an overview of the project structure and key elements.

Methodology
Data Cleaning and Transformation
Data Integrity: The first step was to review the dataset for any errors, such as missing entries or duplicate records. These issues were addressed to ensure accuracy in the analysis.

Data Consolidation: We compared the summary data (monthly revenue) with transaction-level data to ensure consistency and accuracy.

Feature Creation: Several new columns were derived from existing data, such as breaking down the transaction timestamps into more usable formats like Month Name, Weekday Name, and Hour, allowing for deeper analysis of patterns over time.

Handling Outliers: Revenue and sales quantity data were inspected for anomalies or outliers that could distort the results. Appropriate steps were taken to mitigate their impact on the analysis.

Data Transformation
Product Categories: We grouped sales by product category to better understand the performance of each type of offering (e.g., coffee, tea, and hot chocolate).
Store Performance: Sales data was analyzed by store location to identify which stores consistently performed well and which might need support or strategic changes.
Time-Based Insights: By analyzing sales at different times of day and on different days of the week, we uncovered patterns in customer purchasing behavior.
Insights and Recommendations
Key Insights
Best-Selling Products: Coffee remains the top seller across all locations, with notable increases in demand for hot beverages like hot chocolate during the colder months.

Sales Peak Times: The busiest hours for most stores are between 7 AM and 10 AM, indicating that morning customers account for a significant portion of sales.

Location Performance: Stores in Lower Manhattan consistently showed the highest sales volumes, likely due to the area's dense population and strong customer demand.

Recommendations
Inventory Management: It’s recommended to adjust inventory to ensure popular products like coffee are well-stocked during peak morning hours, especially in winter.
Promotional Campaigns: To boost sales during slower times (e.g., mid-afternoon), targeted promotions such as discounts on select items or combo deals could be introduced.
Store Expansion: The success of the Lower Manhattan stores suggests that similar high-traffic locations could be considered for future expansion opportunities.

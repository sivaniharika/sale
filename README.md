**Project Title : **
Advanced  Sales Analytics using Google Looker Studio

Project Description:
This project involves analyzing sales data from a retail company to derive actionable insights and create impactful visualizations using SQL, Python, and Google Looker Studio. The dataset comprises multiple tables (customer_detail, order_detail, sku_detail, and payment_detail) representing customers, orders, products, and payments.


Tools and Technologies Used:
• SQL:
Database creation, querying, and aggregation. o Extracted data using JOIN, GROUP BY, and advanced filtering.

• Python:
Data processing with Pandas for cleaning and transformation. o Visualization using Matplotlib and Seaborn for detailed insights.

• Google Looker Studio:
 Created interactive dashboards with real-time filters and drill-down capabilities. o Integrated SQL-based data for visualization and easy sharing with stakeholders.


Key Steps and Insights
•	Data Preparation
        Tables included:
	customer_detail: Stores customer profiles.
	order_detail: Contains order-level transaction records.
	sku_detail: Holds product information such as pricing and categories.
	payment_detail: Tracks payment types.

•	Analysis and Visualization
1.	Top 5 Products by Sales in 2022 for the "Mobiles & Tablets" Category 
•  Leveraged SQL and Python to determine the top 5 best-selling                            items in the “Mobiles & Tablets” segment based on quantity sold.
•  Displayed the outcomes using bar charts built with visualization tools such as Matplotlib and Seaborn.
2.	Top 20 prodcuts Analyzing Sales Decrease in the "Others" Category Between 2021 and 2022
•	Sales records for the "Others" category were compared year-over-year to measure change in performance. The decline in quantity sold between 2021 and 2022 was computed for each product.
The 20 products with the largest negative difference were identified. 
•	These results were presented through horizontal bar charts, making it easier to visualize the extent of decline and prioritize products needing deeper investigation or marketing attention.





3.	Identifying Customers Who Completed Checkout but Didn't Pay in 2022
•	Customer records were analyzed to find users who reached the checkout stage—indicated by is_gross = 1 but did not complete their payment.

4.	Comparing Weekend and Weekday Sales in Q4 2022 for 3 months
•	Sales data for October, November, and December 2022 was divided into weekend (Saturday–Sunday) and weekday (Monday–Friday) transactions.
Average daily sales (before_discount) were computed separately for each group within all three months.
•	These results were then visualized using bar charts, enabling a direct comparison of weekend vs. weekday performance.

5.	Top 10 Products with the Largest Decrease in Sales Between Two Periods (e.g., 2022 vs 2021)
•	To evaluate declining performance across years, product-wise sales totals for 2021 and 2022 were compared. The change in sales volume was calculated, and the top 10 products with the sharpest decrease were highlighted.
•	Visualization using side-by-side bar charts clearly illustrates the magnitude of decline and assists in identifying products that may require re-pricing, improved marketing, or discontinuation analysis.

6.	Comparing Sales Trends for Multiple Categories in 2022 Scenario(category and sales)
•	Sales trends were examined across several product categories throughout 2022. Monthly sales were aggregated for each category to generate time-series data.
•	A multi-line trend chart was used to visualize how different categories performed month-by-month, enabling teams to identify seasonal peaks, growth patterns, or underperforming segments.
This comparison helps understand which categories drove overall business performance during the year and which ones require strategic attention.



Impact:
The project empowers stakeholders with actionable insights and interactive visualizations, supporting strategic decisions in marketing, sales, and customer management. Google Looker Studio dashboards make the data easily accessible and interpretable, fostering data-driven strategies for better business outcomes.



Apocalypse Store Sales Data Analysis Report
Tool Used: Power BI (Data Cleaning with Power Query, Dashboard Development with Power BI Desktop)

1. Introduction
This project involved analysing the sales performance of a retail business, Apocalypse Store, using a structured dataset comprising four related tables: Apocalypse Sales, Apocalypse Store, Customer Buyer Information, and Customer Information. The purpose of the analysis was to understand product performance, customer purchasing behaviour, and profitability trends across different states and dates.

2. Data Preparation and Cleaning
Data cleaning and transformation were conducted in Power Query to ensure data accuracy and consistency before loading into Power BI.
Key steps included:
•	Merging tables using Cust ID as the primary key to create a unified model.
•	Removing duplicates and handling missing data values to maintain dataset integrity.
•	Standardising column names and formats for uniformity.
•	Creating calculated columns such as Total Purchase Value and Profit Margin to support deeper insights.

3. Data Model
The four tables were joined through relational modelling based on Cust ID (customer key) and Product ID (product key). This allowed dynamic filtering and drill-down analysis across customer, product, and sales dimensions.

4. Dashboard and Visualisations
An interactive Power BI dashboard was designed to display key performance indicators and visual insights:
•	KPIs (Cards):
o	Total count of purchases: 50
o	Minimum total purchased: 9
o	Sum of total purchased: 22,000

•	Product Performance:

o	A bar chart showing Product Name vs. Units Sold revealed that Multitool Survival Knife had the highest sales (477 units) while Solar Battery Flashlight recorded the lowest (182 units).

•	Sales Trend Analysis:
o	A line chart displayed Product Purchases by Day of Month. The 21st day recorded the highest sales, led by Duct Tape.

•	Customer Insights:
o	A card chart summarised customer purchases, showing that Uncle Joe’s Prep Shop had the highest number of purchases, while Alex the Analyst Apocalypse Preppers recorded the lowest (613 items).
o	A stacked column chart illustrated Units Sold per Customer segmented by product type, showing diversity in customer buying patterns.

•	Profitability Analysis:
o	A combined line and bar chart compared Production Cost and Price per product. Weather Proof Jacket had the highest profit margin, while N95 Mask had the lowest.

•	Geographic Distribution:
o	A ring (donut) chart visualised Purchases by State. The state of MN (Minnesota) recorded the highest total purchases (6,061), while FL (Florida) recorded the lowest (1,212), highlighting strong regional sales differences.

5. Insights & Findings
•	Multitool Survival Knife emerged as the top-selling item, indicating strong customer demand for multi-purpose tools.
•	Sales peaked around the 21st of each month, suggesting a potential pattern tied to customer purchasing cycles or promotions.
•	High-value customers like Uncle Joe’s Prep Shop contributed significantly to total revenue, representing key retention targets.
•	Profit margins varied widely across products, highlighting opportunities to reassess pricing or cost efficiency — particularly for low-margin items like N95 Masks.
•	Regional sales data revealed that Minnesota (MN) was the top-performing state, while Florida (FL) had the lowest purchase volume, suggesting geographic differences in product demand.

6. Conclusion
This analysis provided actionable insights into product performance, customer segmentation, and profitability for Apocalypse Store. By leveraging Power Query for efficient data cleaning and Power BI for dynamic visualization, the project demonstrated the power of data analytics in driving evidence-based business decisions.

7. Recommendations
•	Increase inventory for high-performing products such as Multitool Survival Knife and Weather Proof Jacket.
•	Investigate low-margin products to optimise pricing and production costs.
•	Target top customers with loyalty programs to maintain engagement.
•	Focus marketing and promotional efforts in low-performing states like Florida to improve sales balance.
•	Monitor monthly sales spikes (especially around the 21st) to plan marketing and supply accordingly.


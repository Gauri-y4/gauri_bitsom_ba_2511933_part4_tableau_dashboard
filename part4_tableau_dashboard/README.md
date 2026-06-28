\## Data Inspection and Assumptions



The dataset was successfully connected to Tableau and inspected before creating visualizations.



The following field types were identified:



\*\*Date Fields\*\*



\* Order Date

\* Ship Date



\*\*Geographic Fields\*\*



\* Region

\* State

\* City



\*\*Categorical Fields\*\*



\* Category

\* Sub Category

\* Customer Segment

\* Ship Mode

\* Campaign Channel



\*\*Numerical Measures\*\*



\* Sales

\* Profit

\* Discount

\* Customer Rating

\* Delivery Days



\*\*Binary / Flag Fields\*\*



\* Returned



\### Assumptions



\* Tableau correctly detected the data types for all fields.

\* Order Date is used for time-based analysis.

\* Sales and Profit are treated as continuous numerical measures.

\* Returned is treated as a binary field for return analysis.

\* No data type changes were required before creating the dashboard.



\---



\## Calculated Fields



\### Profit Margin

Calculated as Profit ÷ Sales. It measures how much profit is earned from each unit of sales.



\### Cost

Calculated as Sales − Profit. It estimates the cost associated with generating sales.



\### Average Order Value

Calculated as Sales ÷ Number of Orders. It measures the average revenue generated per order.



\### Return Rate

Calculated as Returned Orders ÷ Total Orders. It measures the proportion of orders that were returned.



\### Shipping Delay Bucket

Delivery days are grouped into:

\- Fast (0–2 days)

\- Medium (3–5 days)

\- Slow (More than 5 days)



This grouping helps compare shipping performance across different delivery speeds.



\---



\---



\# Business Problem Summary



The objective of this project is to develop an executive Tableau dashboard that enables business leaders to monitor sales performance, profitability, customer behavior, regional performance, shipping efficiency, discount impact, and product returns. The dashboard is designed to support data-driven decision-making by presenting key business metrics and interactive visualizations in a single view.



\---



\# Dataset Description



The dataset contains retail sales transactions, customer information, product categories, regional details, shipping information, discounts, profits, and return status. It was used to create interactive visualizations that provide insights into business performance across multiple operational areas.



\---



\# Tableau Workbook Description



The Tableau workbook (`executive\_dashboard.twbx`) contains individual worksheets for sales trends, regional performance, category profitability, customer segment analysis, shipping performance, discount versus profit analysis, and return analysis. These worksheets are combined into a single interactive executive dashboard with KPI cards, filters, and dashboard actions.



\---



\# Dashboard Components



The executive dashboard includes:



\* KPI Cards (Total Sales, Total Profit, and Profit Margin)

\* Monthly Sales Trend

\* Regional Sales Performance

\* Category Profitability

\* Customer Segment Performance

\* Shipping Performance

\* Discount vs Profit Analysis

\* Return Analysis



\---



\# Filters and Interactions Used



The dashboard includes interactive filters for Region, Category, and Customer Segment, allowing users to explore the data dynamically.



A dashboard filter action has also been implemented. Selecting a region in the Regional Sales Performance chart automatically filters the remaining dashboard views, allowing users to analyze regional performance across all business metrics.



\---



\# Key Business Insights



The dashboard highlights several important business insights:



\* Sales remain relatively stable throughout the year.

\* The South region demonstrates strong sales performance.

\* Technology is the most profitable product category.

\* The Consumer segment generates the highest sales.

\* Higher discounts are generally associated with lower profitability.

\* Shipping performance varies across different shipping modes.

\* Furniture records the highest number of product returns.

\* Reducing unnecessary discounts and product returns presents an opportunity to improve overall profitability.



\---



\# Dashboard Story Summary



The dashboard provides leadership with a consolidated view of business performance by connecting sales trends, profitability, customer behavior, regional performance, shipping efficiency, discounts, and product returns. While overall sales remain strong and consistent, the dashboard identifies opportunities to improve profitability through optimized discount strategies, reduced return rates, and stronger performance in lower-performing regions. The dashboard supports informed strategic decision-making through interactive visual analysis.



\---



\# Assumptions and Limitations



\## Assumptions



\* The dataset accurately represents retail business operations.

\* All calculated fields were created using standard business formulas.

\* Tableau correctly interpreted the imported data types.



\## Limitations



\* The dashboard provides a high-level business overview and does not identify root causes behind trends.

\* External factors such as competitor activity, economic conditions, and customer demographics are not included.

\* The dashboard demonstrates business relationships but does not establish causation.



\---



\# Screenshots Included



The repository includes the following screenshots:



\* `full\_dashboard.png`

\* `sales\_trend\_view.png`

\* `regional\_performance\_view.png`

\* `category\_profitability\_view.png`

\* `filter\_interaction\_view.png`




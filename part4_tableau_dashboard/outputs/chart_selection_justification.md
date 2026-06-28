\# Chart Selection Justification



\---



**# Task 6: Visualization Design Principles**



\## 1. Correct Chart Selection



\*\*Monthly Sales Trend (Line Chart):\*\* A line chart was used to show sales trends over time, making it easy to identify monthly increases and decreases.



\*\*Regional Sales Performance (Horizontal Bar Chart):\*\* A bar chart allows quick comparison of sales across different regions.



\*\*Category Profitability (Stacked Bar Chart):\*\* A stacked bar chart compares profit across product categories while showing contributions from different subcategories.



\*\*Sales by Customer Segment (Bar Chart):\*\* A bar chart clearly compares sales among different customer segments.



\*\*Average Delivery Days by Ship Mode (Bar Chart):\*\* A bar chart effectively compares delivery times across shipping methods.



\*\*Discount vs Profit (Scatter Plot):\*\* A scatter plot was chosen to visualize the relationship between discount and profit and identify any correlation or outliers.



\*\*Returns by Category (Bar Chart):\*\* A bar chart makes it easy to compare return counts between product categories.



\## 2. Clear Hierarchy



The dashboard places KPI cards (Total Sales, Total Profit, and Profit Margin) at the top to provide a quick business summary. Trend analysis is displayed next, followed by detailed performance charts.



\## 3. Minimal Clutter



Only relevant charts and filters were included. Unnecessary decorations, gridlines, and excessive text were avoided to keep the dashboard clean and easy to read.



\## 4. Consistent Color Usage



A consistent color palette was used throughout the dashboard. Similar colors represent related business measures, helping users interpret the charts quickly.



\## 5. Proper Labels



Every chart includes descriptive titles and clearly labeled axes where applicable. KPI cards are also clearly labeled for easy understanding.



\## 6. Readable Titles



Each visualization has a meaningful title, such as \*Monthly Sales Trend\*, \*Regional Sales Performance\*, and \*Discount vs Profit Relationship\*, making the purpose of each chart immediately clear.



\## 7. Appropriate Sorting



Bar charts were arranged logically to improve readability and comparison between categories and regions.



\## 8. Useful Filters



Interactive filters such as Region, Category, and Customer Segment allow users to explore the dashboard based on their business requirements.



\## 9. Avoidance of Misleading Scales



Default Tableau scales were maintained without manipulation, ensuring an accurate and honest representation of the data.



\## 10. Focus on Business Interpretation



The dashboard is designed for executives to quickly monitor business performance, identify profitable categories, analyze regional sales, evaluate shipping performance, understand customer segments, examine the relationship between discounts and profit, and monitor product returns for informed decision-making.



\---



**# Task 10: Chart Selection Justification**



\## 1. Monthly Sales Trend



\*\*Business Question:\*\* How has monthly sales performance changed over time?



\*\*Why this chart type?\*\*  

A line chart is the most appropriate visualization for time-series data because it clearly highlights trends, fluctuations, and seasonal patterns.



\*\*Fields Used:\*\*

\- X-axis: Month

\- Y-axis: Sales

\- Filter: Region, Category, Customer Segment



\*\*Design Principle Applied:\*\*  

A clean line chart emphasizes trends while minimizing visual clutter.



\*\*Mistake Avoided:\*\*  

A bar or pie chart would make it more difficult to identify changes in sales over time.



\---



\## 2. Regional Sales Performance



\*\*Business Question:\*\* Which regions generate the highest sales?



\*\*Why this chart type?\*\*  

A horizontal bar chart allows quick comparison of sales across different regions and makes ranking straightforward.



\*\*Fields Used:\*\*

\- Category: Region

\- Measure: Sales

\- Color: Sales

\- Filter: Region



\*\*Design Principle Applied:\*\*  

Bars are sorted by sales to improve comparison and readability.



\*\*Mistake Avoided:\*\*  

A pie chart would make it difficult to compare similar sales values accurately.



\---



\## 3. Category Profitability



\*\*Business Question:\*\* Which product categories contribute the most profit?



\*\*Why this chart type?\*\*  

A stacked bar chart allows both category-level comparison and the contribution of sub-categories to be viewed simultaneously.



\*\*Fields Used:\*\*

\- Category: Product Category

\- Measure: Profit

\- Color: Sub-Category



\*\*Design Principle Applied:\*\*  

Consistent colors help distinguish sub-categories while maintaining an organized layout.



\*\*Mistake Avoided:\*\*  

Displaying every sub-category separately would make the visualization unnecessarily cluttered.



\---



\## 4. Customer Segment Performance



\*\*Business Question:\*\* Which customer segment generates the highest sales?



\*\*Why this chart type?\*\*  

A bar chart enables direct comparison between customer segments and clearly highlights the strongest-performing segment.



\*\*Fields Used:\*\*

\- Category: Customer Segment

\- Measure: Sales

\- Color: Customer Segment



\*\*Design Principle Applied:\*\*  

Simple categorical comparison improves readability and supports quick decision-making.



\*\*Mistake Avoided:\*\*  

Complex charts were avoided because only three customer segments are being compared.



\---



\## 5. Shipping Performance



\*\*Business Question:\*\* How does delivery performance differ across shipping modes?



\*\*Why this chart type?\*\*  

A bar chart provides a clear comparison of average delivery days for each shipping mode.



\*\*Fields Used:\*\*

\- Category: Ship Mode

\- Measure: Average Delivery Days

\- Color: Shipping Delay Bucket



\*\*Design Principle Applied:\*\*  

Consistent formatting makes it easy to compare delivery performance across shipping methods.



\*\*Mistake Avoided:\*\*  

A line chart was avoided because shipping modes do not represent a time sequence.



\---



\## 6. Discount vs Profit



\*\*Business Question:\*\* How do discounts affect profitability?



\*\*Why this chart type?\*\*  

A scatter plot is the most appropriate chart for examining the relationship between two numerical variables.



\*\*Fields Used:\*\*

\- X-axis: Discount

\- Y-axis: Profit

\- Color: Profit Margin



\*\*Design Principle Applied:\*\*  

Individual data points make patterns, trends, and potential outliers easier to identify.



\*\*Mistake Avoided:\*\*  

Aggregated charts were avoided because they would hide the relationship between individual observations.



\---



\## 7. Return Analysis



\*\*Business Question:\*\* Which product categories experience the highest number of returns?



\*\*Why this chart type?\*\*  

A bar chart enables clear comparison of return counts across categories.



\*\*Fields Used:\*\*

\- Category: Product Category

\- Measure: Returned Orders

\- Color: Return Flag



\*\*Design Principle Applied:\*\*  

Simple comparisons help leadership quickly identify categories requiring attention.



\*\*Mistake Avoided:\*\*  

Using multiple colors or unnecessary visual elements was avoided to keep the chart focused on the business problem.



\---



\## Overall Dashboard Design



The dashboard follows executive dashboard design principles by presenting key performance indicators at the top, followed by detailed analytical views. Consistent color usage, meaningful titles, appropriate chart selection, interactive filters, and dashboard actions enable leadership to quickly explore business performance while maintaining a clean and professional layout.


This interactive dashboard provides a comprehensive view of the Superstore's historical sales and profitability performance from 2014 to 2017. It is designed to inform strategic decisions related to product management, regional focus, and operational efficiency.

Objective: Track Key Performance Indicators (KPIs) and identify trends across sales, profit, and product categories.

Data Source: Sample - Superstore (Retail/Financial Dataset)

Tool: Power BI / Tableau (specify which one you used)

Target Audience: Business Stakeholders and Executive Management.

2. Key Performance Indicators (KPIs)
The following KPIs are displayed in the top card row and throughout the dashboard:

KPI	Calculation	Business Question Answered
Total Sales	SUM(Sales)	What is the total revenue generated across the selected period/filters?
Total Profit	SUM(Profit)	What are the total earnings after accounting for costs?
Profit Ratio	 
Total Sales
Total Profit
​
 	How profitable are we per dollar of sales? (Our overall efficiency)
YoY Sales Growth %	 
Prior Year Sales
(Current Sales−Prior Year Sales)
​
 	Are we growing? What is the sales momentum compared to the same period last year?
Average Order Value (AOV)	 
DISTINCTCOUNT(Order ID)
Total Sales
​
 	How much does a customer spend, on average, per transaction?

Export to Sheets
3. Dashboard Sections & Insights
Visual Section	Purpose & Analysis
Interactive Filters (Left Sidebar)	Allows users to drill down by Year, Region, or Product Category to focus the entire dashboard on specific segments.
Quarterly Performance Trend	Time-Series Analysis. Shows the revenue and profit lines over time. This helps identify seasonality, peak sales quarters (usually Q4), and periods of declining profitability.
Profit Ratio % Trend	Time-Series Analysis. Focuses specifically on the margin to show when efficiency increases or decreases, independent of raw sales volume.
Top Selling Product Sub-Categories	Identifies which sub-categories (e.g., Binders, Phones, Chairs) are driving the most revenue, guiding inventory and marketing focus.
Sales vs. Profit by Region	Compares raw sales and profit across the Central, East, South, and West regions to highlight regional strengths and problem areas (e.g., high sales but low profit in one region).

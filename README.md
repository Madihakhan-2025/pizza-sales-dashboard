# pizza-sales-dashboard

## Problem Statement

The pizza company lacks a centralised system to monitor and analyze its sales data, making it difficult to identify top-performing products, seasonal trends, and underperforming items. Without actionable insights, decision-makers struggle with menu optimization, promotional planning, and inventory management. This dashboard aims to transform raw order data into a visually engaging and interactive report, enabling stakeholders to quickly assess revenue drivers, customer preferences, and operational bottlenecks.

## Steps Followed to Build the Dashboard

1.	Data Understanding & Cleaning
o	Explored pizza sales dataset tables (orders, order_details, pizzas, pizza_types)
o	Checked for duplicates, missing values, and standardized data types
2.	Data Modeling
o	Built relationships between tables using primary and foreign keys
o	Ensured one-to-many joins (e.g., order_id between orders and order_details)
3.	Measure Creation (DAX)
o	Created key measures: total revenue, quantity sold, average monthly revenue, etc.
o	Used CALCULATE, SUMX, TOPN, and VAR functions to create dynamic insights
4.	Visual Design
o	Developed clean, intuitive charts:
	Bar and line charts for trends
	Pie chart for category breakdown
	Cards for KPIs (revenue, quantity)
o	Used slicers (month, size) for interactivity

Explanation:-

**KPI Cards (Top Row)**
•	Total Revenue: Displays overall sales performance in dollars.<img width="141" height="87" alt="Image" src="https://github.com/user-attachments/assets/472cb85e-4a88-4080-92e5-f2150503d499" />

•	Average Monthly Revenue: Measures consistent earning power over time
<img width="101" height="42" alt="Image" src="https://github.com/user-attachments/assets/b4e3c877-b83b-4abb-9dce-3e27b0192677" />

•	Total Quantity Sold: Indicates volume of pizzas sold — useful for ops planning
•	Total Orders: Reflects order frequency and customer activity

**Monthly and Quarterly Revenue Trends (Combo Chart)**
•	Line + Bar combo chart showing revenue by month and quarter

•	Helps identify:
o	Seasonal peaks or slowdowns
o	Growth momentum or decline across time

**Top 10 Pizzas by Revenue (Bar Chart)**
•	Visualizes the top-selling pizza types
•	Highlights best-performing products — like big_meat_s

**Pizza Category Distribution (Donut/Pie Chart)**
•	Breaks down sales by category: Classic, Veggie, Chicken, Supreme
•	Reveals customer preferences across flavor profiles. 
<img width="175" height="102" alt="Image" src="https://github.com/user-attachments/assets/464b8e50-1385-4954-a4f8-591a0b7e27e2" />

**Day vs. Time Sales Patterns (Heatmap or Matrix)**
•	Compares quantity sold by day of the week and time of day.
•	Pinpoints busy hours (e.g., weekends & evenings) vs. low-demand windows. <img width="154" height="64" alt="Image" src="https://github.com/user-attachments/assets/13a4a008-d8b8-49e2-9af4-ee7750eac3ac" />

Helps with staffing schedules and promo timing

**Slicers: Month and Pizza Size**
•	Interactive filters to adjust visuals:
o	View trends for specific months
o	Analyze performance by size (S, M, L, XL)
<img width="232" height="95" alt="Image" src="https://github.com/user-attachments/assets/0bf635b3-82ea-4d34-b1fe-157e399e9e79" />

**Tooltips (Hidden Pages)**
•	Pop-up summaries appear when hovering over visuals
•	Deliver more details without overwhelming the main page
5.	Dashboard Optimization
o	Aligned visuals, added titles, themes, and tooltips for usability
o	Ensured consistent color scheme and layout
  
**Summary**

The Pizza Sales Dashboard’s core purpose is to turn raw transaction data into a clear, interactive view of performance, spotlighting best- and worst-selling pizzas, revenue trends over time, and category breakdowns. Its goal is to equip stakeholders with actionable insights—so they can optimize the menu, tailor promotions, manage inventory, and drive strategic growth—by making complex sales patterns instantly understandable through dynamic visuals and intuitive filters.

**Things that I learned:-**

🧠 DAX formulas for custom calculations (e.g., revenue, rankings)

🔗 Data modeling and establishing relationships between tables

📦 CALCULATE + SUMX + VAR patterns for flexible measures

🎯 TOPN for finding top/least performing items

📊 Visual storytelling using cards, charts, and slicers

⚙️ Basic troubleshooting for Power BI and ChatGPT issues


**SNAPSHOT OF DASHBOARD **

<img width="959" height="436" alt="Image" src="https://github.com/user-attachments/assets/620ef02e-9bee-4851-8b02-f034e62216ef" />

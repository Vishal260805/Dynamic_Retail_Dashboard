📊 Dynamic Retail Dashboard - Walmart Mini Project (Excel)

This repository presents a Dynamic Retail Dashboard created using Microsoft Excel and Power Query, leveraging Walmart retail data to uncover valuable business insights. The dashboard integrates data from multiple sources and solves key analytical problems through dynamic visualizations.

📊 Business Problem

With growing demands and cut-throat competition in the market, Walmart is seeking insights to understand what strategies work best. The company has collected recent sales data to:

Identify trends in its operations

Improve efficiency

Optimize decision-making through data

🔄 Objective

Our objective is to explore the performance of Walmart stores and identify opportunities for improvement. Using Exploratory Data Analysis (EDA) in Excel, we examined customer segments, product categories, markets, and sales data to generate actionable insights. The dashboard dynamically showcases KPIs, trends, and patterns.

📂 Dataset Overview

✅ Orders Table

Contains transactional details for each customer order including sales, profit, quantity, discounts, and shipping.

Sample Columns:

Order ID, Order Date, Ship Date, Customer Name, Segment, Country, Market

Category, Sub-Category, Product Name

Sales, Quantity, Profit, Discount, Shipping Cost, Order Priority

✅ Returns Table

Tracks returned orders with associated market.

Columns: Returned, Order ID, Market

✅ People Table

Lists salespeople and their assigned regions.

Columns: Person, Region

💡 Technical Implementation

Data Source: Excel file hosted on GitHub

Power Query: Used to import and transform data from all 3 tables

Pivot Tables & Charts: For dynamic visualization

Slicers: For user-interactive filtering (Segment, Region, Category, Year)

🔹 Problem Statements & Solutions

1. 💼 KPIs (Key Performance Indicators)

Objective: Track total sales, total profit, quantity sold, number of orders, and profit margin.

Steps:

Create calculated columns:

Profit Margin = Profit / Sales

Use SUM, COUNTA, COUNTIF functions for totals

Display KPIs using icons, conditional formatting, and colored cards

Insight:

KPIs reveal how well the business is performing in revenue and margin. A low profit margin could signal pricing issues or high costs.
<img width="878" height="166" alt="Screenshot 2025-07-21 183228" src="https://github.com/user-attachments/assets/77fb823c-5639-4d2a-94fa-297ab3d9ec42" />


2. 📊 Sales and Profit Analysis

Objective: Explore trends of sales and profit over time.

Steps:

Create Pivot Table grouped by Year and Month

Add Sales and Profit to values

Create Line Chart for trends

Use slicers for Year, Region, and Segment

Insight:

Trendlines show peak seasons and potential loss periods. Helps in seasonal planning and performance comparison year over year.
<img width="896" height="70" alt="Screenshot 2025-07-21 183311" src="https://github.com/user-attachments/assets/2875e679-cf4c-480e-9b1d-bd4c376ccf5e" />

3. 🏘️ Category-wise Profit

Objective: Analyze profitability across categories (Furniture, Technology, Office Supplies).

Steps:

Pivot Table: Category as rows, Profit as values

Sort descending

Bar Chart for visualization

Insight:

Certain categories consistently drive higher profits. This helps prioritize inventory and marketing efforts.
<img width="356" height="321" alt="Screenshot 2025-07-21 183458" src="https://github.com/user-attachments/assets/da2a001f-3656-423a-856f-d14b5eb02bca" />


4. 🤝 Segment-wise Sales Share %

Objective: Show what portion each customer segment contributes to total sales.

Steps:

Pivot Table with Segment and Sales

Calculate % Share = Sales / Total Sales

Donut Chart with percentage labels

Insight:

Identifies if Consumer, Corporate, or Home Office customers are more valuable to the business.
<img width="378" height="322" alt="Screenshot 2025-07-21 183532" src="https://github.com/user-attachments/assets/330354d9-4f8f-458f-a529-62ebaf370ae1" />


5. 🌏 Sales by Country

Objective: View which countries bring the most revenue.

Steps:

Pivot Table with Country and Sales

Apply Conditional Formatting or use a Map Chart

Insight:

Countries with low sales can be targeted for campaigns or logistics optimization. Top countries can be further segmented.
<img width="539" height="337" alt="Screenshot 2025-07-21 183602" src="https://github.com/user-attachments/assets/94036def-72a2-4920-baf6-d28df7418e5a" />


6. 🏆 Top 5 Subcategories

Objective: Identify top-performing subcategories by sales.

Steps:

Pivot Table: Sub-Category and Sales

Sort descending

Filter Top 5

Column Chart for visualization

Insight:

Helps businesses focus on bestsellers and align supply chains accordingly.
<img width="445" height="321" alt="Screenshot 2025-07-21 183631" src="https://github.com/user-attachments/assets/738be555-fb7c-4d07-8f03-deaa09a121b4" />


7. ❌ Bottom 5 Subcategories

Objective: Highlight underperforming subcategories.

Steps:

Reuse above Pivot Table, sort ascending

Filter Bottom 5

Use Column Chart with red color for emphasis

Insight:

Poor sales may signal product issues, low demand, or ineffective promotions.
<img width="471" height="326" alt="Screenshot 2025-07-21 183648" src="https://github.com/user-attachments/assets/5334bc3e-c493-4247-8dce-d830d4bf9457" />


8. 📅 Yearly Sales Trend

Objective: Analyze overall performance over multiple years.

Steps:

Pivot Table: Group Order Date by Year

Sales in Values

Line Chart with Slicers for Category, Market, Segment

Insight:

Year-over-year trends support strategic forecasting and show impact of external events or campaigns.
<img width="411" height="326" alt="Screenshot 2025-07-21 183720" src="https://github.com/user-attachments/assets/03c004be-7cbf-459a-aa5f-46c72219e143" />


📊 Visuals

KPI Cards with dynamic metrics

Interactive Slicers

Line Charts, Bar Charts, Pie Charts

Conditional Formatting & Heat Maps

Screenshots for each solution are included in the repository.
<img width="1321" height="649" alt="Screenshot 2025-07-21 183944" src="https://github.com/user-attachments/assets/8e5ef687-5537-446c-8e1e-a4d3b640244e" />


📜 Repository Structure

Retail-Dashboard-Walmart/
├── data/
│   ├── Orders.xlsx
│   ├── Returns.xlsx
│   └── People.xlsx
├── visuals/
│   └── [Charts & KPI screenshots]
├── dashboard/
│   └── Walmart_Retail_Dashboard.xlsx
├── README.md

✅ Outcome

This project helps Walmart:

Optimize operations

Understand customer behavior

Identify profitable categories and segments

Make strategic, data-backed decisions

© License

Open-source project under MIT License.

🙋‍ Contact

Built by Vishal Bhardwaj. For feedback or queries, reach out via GitHub Issues.


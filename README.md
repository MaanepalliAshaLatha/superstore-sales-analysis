🏪 Global Superstore Profitability Analysis

Tools: MySQL, Excel, Pivot Tables
Dataset: 51,290 orders across 147 countries (2012–2015)
Goal: Identify why a high-revenue global store was losing money.

📌 Business Problem

Global Superstore generated strong sales but inconsistent profitability.
The goal was to find which products, discount levels, and regions contributed most to losses and quantify their impact.

🔍 Key Findings

84.83% of total losses were caused by discounts of 40% or more.
Tables were the highest loss contributor (around −$1.11L under high discounts).
Machines were the second-highest loss contributor (around −$72K).
Technology was the highest revenue category (about $827K).
The Consumer segment represented 51% of all orders.

🛠️ SQL Techniques Used

CTEs (WITH clause) to isolate discount groups
CASE WHEN to classify orders into discount bands
GROUP BY with SUM(Profit) to aggregate losses
ORDER BY to rank sub-categories by total loss
JOINs to merge order and product tables

📊 Excel Dashboard

The multi-sheet Excel dashboard includes:

Revenue by Segment (Consumer, Corporate, Home Office)
Revenue by Category (Furniture, Office Supplies, Technology)
Revenue by Region (West, East, Central, South)
Lookup tool for segment-level drill-down
Above-Average Sales flag
Value-Tier classification logic

💡 Business Recommendations

Cap discounts at 30% for Tables and Machines.
Flag all sub-categories with negative profit margins for review.
Expected margin recovery: ₹80,000–90,000 without major volume loss.

📁 Files in This Repository

Global_Superstore2.csv — raw dataset
queries.sql — SQL queries used in analysis
Analysis.xlsx — Excel pivot tables and dashboard
README.md — documentation

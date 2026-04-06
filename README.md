🏪 Global Superstore Profitability Analysis<br>
Tools: MySQL, Excel, Pivot Tables<br>
Dataset: 51,290 orders across 147 countries (2012–2015)<br>
Goal: Find why a high-revenue global store was losing money.<br><br>

📌 Business Problem<br>
Global Superstore generated strong sales but inconsistent profitability. The goal was to identify which products, discount levels, and regions contributed most to losses and measure their impact.<br><br>

🔍 Key Findings<br>
• 84.83% of total losses were caused by discounts of 40% or more<br>
• Tables were the highest loss contributor (around −$1.11L under high discounts)<br>
• Machines were the second-highest loss contributor (around −$72K)<br>
• Technology was the highest revenue category (about $827K)<br>
• The Consumer segment represented 51% of all orders<br><br>

🛠️ SQL Techniques Used<br>
• CTEs (WITH clause) to isolate discount groups<br>
• CASE WHEN to classify orders into discount bands<br>
• GROUP BY with SUM(Profit) to aggregate losses<br>
• ORDER BY to rank sub-categories by total loss<br>
• JOINs to merge order and product tables<br><br>

📊 Excel Dashboard<br>
The multi-sheet Excel dashboard includes:<br>
• Revenue by Segment (Consumer, Corporate, Home Office)<br>
• Revenue by Category (Furniture, Office Supplies, Technology)<br>
• Revenue by Region (West, East, Central, South)<br>
• Lookup tool for segment-level drill-down<br>
• Above-Average sales flag<br>
• Value-Tier classification columns<br><br>

💡 Business Recommendations<br>
1. Cap discounts at 30% for Tables and Machines<br>
2. Flag sub-categories with negative margins for review<br>
3. Margin recovery expected: ₹80,000–90,000<br><br>

📁 Files in This Repository<br>
• Global_Superstore2.csv — raw dataset<br>
• queries.sql — SQL queries<br>
• Analysis.xlsx — Excel pivot tables & dashboard<br>
• README.md — documentation<br>

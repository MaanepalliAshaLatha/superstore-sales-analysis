🏪 <b>Global Superstore Profitability Analysis</b><br><br>

<b>Tools:</b> MySQL, Excel<br>
<b>Dataset:</b> 51,290 orders across 147 countries<br><br>

<b>📌 Business Problem</b><br>
The business was experiencing significant losses despite strong sales volume.<br>
This analysis identifies how discounting impacts profitability across products and categories, and determines whether losses are driven by discount strategy or product-level pricing gaps.<br><br>

<b>❓ Key Questions</b><br>
• At what discount level do products become unprofitable?<br>
• How much loss is contributed by high-discount ranges?<br>
• Which products are most affected by discounting?<br>
• Are losses driven by discount strategy or inherent product issues?<br><br>

<b>📊 Key Insights</b><br>
• Discounts ≥40% contribute ~85% of total losses — the exact tipping point for profitability.<br>
• Machines and Phones remain profitable at low discounts but turn loss-making under heavy discounting.<br>
• Tables and certain furniture items remain unprofitable even at lower discounts, indicating pricing or cost inefficiencies.<br><br>

<b>🧩 Product Segmentation</b><br>
🟢 <b>Discount-Sensitive:</b> Machines, Phones — profitable → become loss at high discounts.<br>
🟡 <b>Weak-Margin Products:</b> Tables — low margin → easily turn loss.<br>
🔴 <b>Always-Loss Items:</b> Some furniture — structural pricing issue.<br><br>

<b>💼 Business Recommendations</b><br>
• Cap discounts at 40% for high-margin products and 20% for low-margin items to prevent losses.<br>
• Avoid heavy discounting on weak products; use bundling strategies (e.g., tables + bookcases) to improve margins.<br>
• Reevaluate pricing or cost structure for consistently loss-making items.<br><br>

<b>📈 Approach</b><br>
• Analyzed 51K+ orders using MySQL (CTEs, CASE WHEN, Joins).<br>
• Segmented transactions by discount brackets, categories, and sub-categories.<br>
• Built an Excel dashboard to validate trends and visualize loss concentration.<br><br>

<b>📁 Repository Structure</b><br>
• Data_Analysis.docx<br>
• Global_Superstore2.csv<br>
• queries.sql<br>
• dashboard.png<br>
• README.md → Documentation<br>

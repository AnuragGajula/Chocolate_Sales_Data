# Chocolate_Sales_Data
This comprehensive analysis explores chocolate sales performance across countries, products, and time periods to identify key trends, top performers, and growth opportunities.

📌 Project Overview
This project analyzes a dataset of chocolate sales across six countries (Australia, Canada, India, New Zealand, UK, USA) to:

Compare country performance against global averages

Identify seasonal trends and best-selling products

Evaluate salesperson performance and shipping efficiency

Generate actionable business recommendations

📂 Dataset Structure
The dataset contains 1,094 transactions with these key columns:

Column	Description
Sales Person	Name of sales representative
Country	Market where sale occurred
Product	Chocolate product variant
Amount	Revenue generated (in USD)
Boxes Shipped	Quantity of product units sold
Date	Transaction date (2022 only)
Month_Name	Name of month
Year	2022 (fixed year)
Month	Numeric month (1-12)
🔍 Key Insights
🌍 Country Performance
Top Performers: UK (+1.51σ above mean), USA (+0.77σ)

Underperformers: New Zealand (-0.95σ), Canada (-0.89σ)

Australia Paradox: Lowest avg. transaction value but highest shipment volume

📈 Trends
Peak Month: August (holiday season boost)

Worst Month: January (post-holiday slump)

🍫 Product Analysis
Best Sellers: 85% Dark Bars, Almond Choco

Revenue Efficiency: India generates highest revenue per box shipped

🛠️ Technical Implementation
The analysis uses:

Python (pandas, numpy, matplotlib, seaborn)

Statistical Methods: Z-score standardization, trend decomposition

Visualizations:

Comparative bar charts

Time-series line plots

Scatter plots (volume vs. revenue)

💡 Business Recommendations
Market	Strategy
UK/USA	Focus on premium products & wholesale contracts
Australia	Implement upselling tactics to increase transaction value
Canada/NZ	Run targeted promotions to stimulate demand
India	Scale successful premium product strategy

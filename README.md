# TechHub-Retail-Executive-Dashboard

<img width="1349" height="761" alt="Screenshot 2025-10-31 134006" src="https://github.com/user-attachments/assets/3a7c047d-1280-4513-bbed-2ada964a908d" />

## 🚡End-to-end Tableau business intelligence project integrating sales, customer, and product data to deliver executive KPIs, segmentation insights, and a 2025 growth strategy.
### This project integrates three structured datasets in Tableau using relationships and calculated fields to build an executive-level dashboard. The analysis covers profitability trends, customer lifetime value, acquisition performance, seasonal forecasting, and supplier evaluation. Designed to support data-driven strategic decisions for retail growth planning.

Table of Content

- [ProjectOverview](#project-overview)
- [Business Problem](#business-problem)
- [Tools & Technologies](#tools-&-technologies)
- [Data Integration](#data-integration)
- [Multi-Dataset Integration](#multi-dataset-integration)
- [Feature Engineering & KPIs](#Feature-engineering-&-kpis)
- [Dashboard Highlights](#dashboard-highlights)
- [Key Insights](#key-insights)
- [Strategic Recommendations](#strategic-recommendations)
- [



### 🏢Project Overview
This project delivers an end-to-end Business Intelligence solution for a UK-based online electronics retailer. Using Tableau, I integrated multi-source retail data to build an executive dashboard that analyzes revenue growth, profitability, customer lifetime value, product performance, and seasonal trends.
The dashboard supports data-driven strategic planning for 2025 through KPI tracking, segmentation analysis, and forecasting.

### 🎯Business Problem
TechHub Retail lacked a centralized analytics system to:
- Identify high-margin product categories
- Evaluate supplier performance
- Measure customer lifetime value
- Assess acquisition channel effectiveness
- Detect seasonal sales patterns
- Forecast future revenue
This project addresses that gap through structured data modelling and interactive BI visualisation.

### 🛠Tools & Technologies
- Tableau Public
- Multi-dataset data modeling using Relationships
- FIXED LOD expressions
- Table calculations for MoM growth
- Forecasting & trend analysis
- KPI engineering

### 🔗Data Integration
Three datasets were integrated:
- Sales transactions
- Customer demographics & acquisition data
- Product & supplier information
  
Relationships were created between:
- Sales → Customers
- Sales → Products
<img width="621" height="305" alt="Screenshot 2025-10-29 145827" src="https://github.com/user-attachments/assets/7828843d-b4db-42a3-8a3a-9ddd0e91a0d4" />

### Multi-Dataset Integration
Integration Method
The datasets were connected using Tableau Relationships instead of physical joins to preserve data grain and prevent duplication.

Relationships Created

Sales.customer_id → Customers.customer_id (Many-to-One)
Sales.product_id → Products.product_id (Many-to-One)

This ensured accurate aggregation when analyzing across customers and products.

### ⚙Feature Engineering & KPIs

Key calculated metrics include:
- 💰Revenue & Profit Amount
- 📈 Profit Margin %
- 🧮 Average Order Value (AOV)
- 👤 Customer Lifetime Value (CLV)
- 📊 Customer Acquisition (MoM)
- ⏳ Product Age Analysis
- 🔄 Revenue Month-over-Month Growth

### 📊Dashboard Highlights
- Executive KPI Panel
- Revenue, Profit Margin, AOV, Customer Growth
- Sales & Profit Trend Analysis
- Dual-axis visualization with moving average and forecast
- Customer Segmentation
- CLV vs Tenure analysis by loyalty tier
- Product & Supplier Performance
- Treemap and ranked supplier profitability
- Geographic Insights
- Regional revenue distribution with drill-down

### 🔎Key Insights
- 📈 Revenue shows consistent upward growth with strong Q4 seasonality
- 💻 Laptops, Smartphones, and Gaming categories drive the highest margins
- ⭐ Gold & Platinum loyalty tiers generate the highest lifetime value
- 📣 Referral and Email channels produce higher-value customers than Paid Ads
- 🕒 Newer products outperform ageing inventory

### 🚀Strategic Recommendations

1.	Prioritize high-margin product categories
2.	Strengthen loyalty and retention programs
3.	Align inventory and marketing with seasonal peaks
4.	Shift acquisition budget toward high-CLV channels

### 📌What This Project Demonstrates
- Strong analytical thinking
- Structured data integration
- Business impact storytelling
- Dashboard design best practices
- Forecasting and performance monitoring

### Conclusion
This TechHub Retail Executive Dashboard integrates sales, customer, and product intelligence into a single decision-support system. It delivers measurable insights into profitability, customer lifetime value, supplier performance, and seasonal forecasting, enabling data-driven strategic planning for 2025



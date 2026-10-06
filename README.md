# FROM TRANSACTIONS TO INSIGHTS: ANALYZING E-COMMERCE SALES AND CUSTOMER BEHAVIOR
## [🌐 Portfolio](https://www.linkedin.com/in/alarape-abdulazeez) [🔗 Read Full Project On Medium](https://medium.com/@alarapeolayiwola/from-data-to-decisions-analyzing-sales-revenue-profitability-growth-d5d018f86aca)
# 📝 Project Overview
This project analyzes e-commerce sales and customer transaction data to uncover patterns in business performance, customer purchasing behavior, and product performance. The analysis examines revenue trends, customer spending and purchase frequency, product and category performance, order outcomes, and key revenue drivers.
The findings were presented through an interactive Power BI dashboard, allowing users to explore business performance across different dimensions and identify opportunities for customer retention, product optimization, and revenue growth.

# Objective
* Analyze sales performance to understand revenue trends and overall business performance.
* Analyze customer spending behavior to identify different customer spending patterns and value segments.
* Evaluate purchase frequency to understand how often customers make purchases and identify repeat-customer behavior.
* Assess product performance to identify top-performing and underperforming products.
* Evaluate category performance to determine which product categories contribute most to revenue and sales.
* Analyze order outcomes to understand order statuses and identify potential areas for improvement.

# 🧰 Tool
| Tool| Purpose|
|-----|--------|
| Power Query	| Cleaning and Transformation |
| PowerBI	| Data Modelling and Visualization |
# Dataset Description
The dataset was obtained from Kaggle. It follows a star schema with one fact tables and three dimension tables.

| Tables|	Description| Rows|
|-------|------------|-----|
|fact_orders	|contains transactional sales records, including information about orders, products, customers, quantities, and sales-related attributes.	|50,000
|Dim_customer|	contains customers details	|10,000
|Dim_product|	Contains information about products offered by the business	|20
|Dim_payment |Contains information about the payment associated with each customer's orders..|50,000
|Dim_calendar| Date covering january 1st 2024 to September 26th 2026|1096
# Data Workflow
Data Collection ↓ Data Cleaning ↓ Data Modeling ↓ Data Analysis ↓ Dashboard Development ↓ Insights & Recommendations

1. Data Collection: The dataset was obtained from Kaggle.
2. Data Cleaning: Ensure data quality, Checked for duplicated records and Promoted Headers
3. Data Transformation: Added Age Group, Purchasing Frequency and Spending Category into the customer table.
4. Data Modeling: Created relationships between tables and designed a star schema for reporting.
5. Data Analysis: Created measures and explored sales, profitability, Product performance trends and customer purchasing behavior.
6. Dashboard Development: Built a three page interactive PowerBI dashboards to visualize key metrics.
7. Reporting: Documented key findings and provided actionable recommendations.
# Data Model
<img width="410" height="304" alt="Screenshot 2026-10-06 102604" src="https://github.com/user-attachments/assets/a6b4fd2b-d6cf-4566-ade3-a56c8a06c358" />


# 📌 Key Insights
## 1. Executive Summary
<img width="589" height="326" alt="Screenshot 2026-10-06 093900" src="https://github.com/user-attachments/assets/b5e7067c-3548-4e91-b472-3b3e11e4f95c" />


* In 2025, the business generated approximately $1.59M in revenue, compared with $1.60M in 2024, representing a slight decline in revenue. Meanwhile, the number of orders increased by approximately 1.05%, indicating that order volume grew slightly despite the decline in revenue.
* Tehran leads city revenue at approximately $1.05M. The top five cities contribute $2.60M (68%) of total revenue, highlighting strong geographic concentration and opportunities to grow other markets.
## 2. Product Performance
<img width="594" height="334" alt="Screenshot 2026-09-28 100842" src="https://github.com/user-attachments/assets/2832ad24-c7b1-4743-832e-dfd38e21219c" />


* Electronics is the leading revenue category, contributing approximately 51% of total revenue. Accessories rank second, generating $0.61M (16%). This shows that the business relies heavily on Electronics for its revenue.
* Some high revenue categories were not among the most quantity sold, showing sales volume does not determine business value.
## 3. Customer Purchasing Behavior
<img width="583" height="328" alt="Screenshot 2026-10-06 094031" src="https://github.com/user-attachments/assets/489b551d-460d-4322-9c85-cad797c36796" />


* 58.91% of customers are repeat buyers, compared with just 3.18% one-time buyers, indicating a strong and stable customer base.
* The Adult segment ($1.55M) and Young Adult ($1.02M) outpaces the older brackets significantly.

# 🎗️ Recommendations
| Priority | Recommendation	| Business Impact	| Suggested Owner|
|----------|----------------|-----------------|----------------|
|High	|Focus on high-value customers|	Increases customer retention, customer lifetime value, and revenue from existing customers.	|Sales & Marketing Team
|High	|Optimize product performance |	Improves product mix, sales performance, and profitability while reducing resources spent on underperforming products. | Product & merchandising Team
|High	|Monitor cancelled, failed, or incomplete orders and investigate potential issues in the purchasing and payment process.|	Reduces lost revenue, improves order completion rates, and enhances the customer experience.|Operation & Customer Team
|Medium	|Monitor sales trends |	Improves demand forecasting, inventory planning, and timing of promotional activities.	|Sales & Operations Team

# Author
Alarape Abdulazeez - Data Analyst

# 🔗 Connect With Me
* [LinkedIn](http://linkedin.com/in/alarape-abdulazeez)
* [Email](alarapeolayiwola@gmail.com)
* [Medium](https://medium.com/@alarapeolayiwola)

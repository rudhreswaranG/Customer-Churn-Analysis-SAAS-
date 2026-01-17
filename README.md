📊 SaaS Customer Churn Analysis (End-to-End Analytics Project)
📌 Project Objective

The objective of this project is to analyze customer churn in a SaaS business and identify the key factors driving customer attrition.
The analysis focuses on understanding churn patterns across subscription tiers, billing frequency, seat size, customer satisfaction, support resolution time, and acquisition sources, and providing data-driven recommendations to improve customer retention.

📂 Dataset Overview

The data for this project was sourced from Kaggle and consists of five related datasets representing customer, subscription, billing, support, and churn information.

Total Accounts: 500

Churned Accounts: 110

Overall Churn Rate: 22%

🔄 Data Processing & Modeling
🐍 Python (Data Cleaning & Feature Engineering)

Cleaned missing and inconsistent values

Created custom ranges using conditional logic:

Seat size buckets (e.g., 1–25, 26–50, 51–75, etc.)

Satisfaction level categorization

Standardized columns for analysis and reporting

🗄️ SQL (Data Integration & Analysis)

Created individual SQL views for each dataset

Selected only business-relevant columns

Joined all views into a single final churn dataset

Ensured only the latest churn status per Account ID was retained

Performed churn analysis by:

Tier

Billing frequency

Seat range

Satisfaction level

Support resolution time

📊 Power BI Dashboard Development

Imported the final churn dataset from SQL

Created DAX measures for:

Total Accounts

Churned Accounts

Churn Rate (%)

Designed an interactive dashboard with:

KPI cards (Overall churn metrics)

Tier-wise and billing frequency churn analysis

Seat size, satisfaction, and resolution time breakdowns

Cross-filtering and tooltips for deeper insights

🔍 Key Insights
Overall

22% overall churn rate across 500 accounts

Churn is consistently influenced by pricing, support delays, and feature limitations

Tier & Billing Frequency

Basic – Annual has the highest churn rate (30%), indicating value and feature gaps

Enterprise – Monthly shows high churn, driven by pricing sensitivity

Pro tier is relatively stable but affected by support and feature issues

Customer Segments

Higher seat customers churn when pricing does not match perceived value

Low satisfaction customers show significantly higher churn

Support resolution time > 24 hours is a major churn driver

Acquisition Source

Customers acquired via Events and Ads show higher churn

Partner referrals and Organic sources demonstrate better retention

🧠 Business Recommendations

Revisit pricing strategy for higher seat customers to prevent value mismatch

Improve support response SLAs, targeting resolution within 24 hours

Enhance features in the Basic Annual plan to reduce high churn

Reassess Enterprise Monthly pricing and packaging

Increase investment in Partner and Organic acquisition channels for better retention

🛠️ Tools & Technologies Used

Python – Data cleaning & feature engineering

SQL – Views, joins, churn analysis

Power BI – DAX, interactive dashboards, visualization

Excel – Initial data exploration

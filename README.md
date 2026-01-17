📊 Customer Churn Analysis – SaaS
🔍 Project Overview

This project presents an end-to-end customer churn analysis for a SaaS business using Python, SQL, and Power BI.
The goal is to identify why customers churn, analyze churn across tiers, billing frequency, customer size, satisfaction, and support experience, and provide actionable business recommendations to reduce churn.

🎯 Objective

Measure overall churn and churn patterns across customer segments

Identify key churn drivers (pricing, support, features, satisfaction)

Compare churn using count vs churn rate for better decision-making

Recommend data-driven actions to improve customer retention

🧰 Tools & Technologies

Python – Data cleaning, feature engineering (seat ranges, satisfaction buckets)

SQL – Views, joins, churn logic, final analytical dataset creation

Power BI – DAX measures, interactive dashboard, business insights

GitHub – Project documentation and version control

📁 Data Source

Dataset downloaded from Kaggle

Consists of 5 related datasets including:

Customer details

Subscription & billing information

Support & resolution data

Satisfaction scores

Churn status & reasons

Raw datasets were transformed into a single final churn dataset for analysis.

🔄 Data Processing Workflow
1️⃣ Python – Data Cleaning & Feature Engineering

Handled missing values and data inconsistencies

Created derived columns using if-else logic:

Seat range buckets

Satisfaction buckets (Low / Medium / High)

Prepared clean tables for SQL ingestion

2️⃣ SQL – Data Modeling & Analysis

Created views for each dataset with required columns

Joined all views into a single final churn table

Ensured only the latest churn status per Account ID was retained

Performed churn analysis by:

Tier

Billing frequency

Seat range

Satisfaction level

Support resolution time

3️⃣ Power BI – Dashboard & DAX

Built key measures using DAX:

Total Accounts

Churned Accounts

Churn Rate

Used churn rate (%) instead of only counts for better comparison

Designed an interactive dashboard with:

Tier-wise churn

Billing frequency impact

Seat range churn behavior

Satisfaction & support analysis

Churn reasons & referral sources

📸 Dashboard Preview:
(Add dashboard screenshot here)

📈 Key Insights
🔹 Overall

Total accounts: 500

Churned accounts: 110

Overall churn rate: 22%

🔹 Tier-Based Insights

Enterprise: 23% churn – driven by support delays & feature gaps

Basic: 22% churn – highest churn in annual plans (30%)

Pro: 21% churn – relatively stable, churn driven by pricing & support

🔹 Billing Frequency

Annual Basic users churn more → lack of perceived value/features

Monthly Enterprise users show higher churn → pricing sensitivity

🔹 Customer Experience Drivers

Majority of churn comes from:

Small customers (1–50 seats)

Low satisfaction scores

Support resolution time > 24 hours

🔹 Business Drivers

Top churn reasons:

Pricing & budget constraints

Feature limitations

Poor support experience

High churn observed from Ads & Event referral sources compared to Partner & Organic sources

🧠 Business Recommendations

1️⃣ Improve Support SLAs

Reduce resolution time to under 24 hours

Prioritize small and high-value customers

2️⃣ Revisit Pricing Strategy

Adjust pricing for high-seat customers with high satisfaction

Rework Enterprise monthly pricing

3️⃣ Enhance Basic Annual Plan

Add core features to prevent commitment regret

4️⃣ Optimize Marketing Spend

Reduce reliance on Ads & Events

Increase investment in Partner & Organic channels

5️⃣ Segment-Based Retention Strategy

Small customers need proactive onboarding & support

High-seat customers need value-based pricing

📌 Conclusion

Churn in this SaaS business is systemic, not random.
It is primarily driven by poor support experience, pricing dissatisfaction, and feature gaps, especially among small customers.
By improving support quality, refining pricing, and enhancing plan value, churn can be significantly reduced.

# User-Behavior-Revenue-Analysis-for-a-Mobile-App
📊 Mobile App User Behavior & Revenue Analysis


📌 Project Overview
This project analyzes user-level behavioral and revenue data from a mobile app to uncover actionable insights into user engagement, churn risk, and monetization patterns. Using Python, I applied RFM segmentation, funnel analysis, and other metrics to understand user lifecycle stages and provide recommendations to improve retention and revenue generation.

🧠 Problem Statement
The app's product team lacked visibility into:

Which users are most valuable

Which segments are at risk of churn

How engagement relates to revenue

This gap made it difficult to prioritize feature development, improve retention, and personalize marketing strategies.

🔧 Tools Used
Python (Pandas, NumPy, Plotly, Matplotlib) – Data preprocessing, segmentation, funnel creation, and visualization

Jupyter Notebook – Exploratory analysis and logic development

🧪 Key Analyses Performed
1. RFM Segmentation
Recency: Based on Days_Since_Last_Login

Frequency: Total number of play sessions

Monetary: Total revenue from in-game purchases

Users were bucketed into quantiles and scored (1–3) on each RFM component

Segments identified:

Champions

Big Spenders

Loyal Customers

At Risk of Churn

Churned Users

2. Funnel Analysis
Built a custom funnel using logic from user play session counts

Tracked drop-offs across:

Signed Up

Low Engagement

Medium Engagement

High Engagement

Visualized funnel using Plotly to highlight engagement attrition

3. Churn Identification
Used Days_Since_Last_Login to flag users with declining engagement

Estimated churn risk and engagement health

4. Activity Proxies
Created proxy metrics for:

Estimated DAU, WAU, MAU using Last_Login

New Users per Day using Signup_Date

📈 Business Impact
Enabled the business to identify champion users and target churn risks for re-engagement

Segmentation supported feature prioritization and retention campaigns

Funnel insights revealed key drop-off points in the user lifecycle

📤 Output Ready for Dashboarding
Cleaned, segmented data exported for visualization in Power BI

Metrics aligned with business goals: retention, engagement, monetization



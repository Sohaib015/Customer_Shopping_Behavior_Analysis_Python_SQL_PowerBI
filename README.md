# Customer_Shopping_Behavior_Analysis
A comprehensive end-to-end project analysing customer shopping behavior using Python, SQL and power Bi. The project involves Data Manipulation, Exploratory Data Analysis and Data storytelling and visualisation enabling us to identify trends and patterns and make informed decisions. 

# Project overview
This project analyzes customer shopping behavior using transactional retail data to uncover actionable insights related to spending patterns, customer segmentation, product performance, and subscription impact. The dataset contains 3,900 purchase records across multiple product categories and behavioral dimensions.
The objective of this analysis is to support data-driven decision-making by identifying revenue drivers, customer engagement trends, and opportunities for strategic growth through analytics.

# Business Problem Statement

A leading retail company seeks to better understand evolving customer purchasing behavior to improve sales performance, customer satisfaction, and long-term loyalty. Shifts in buying patterns across demographics, product categories, and purchasing preferences have raised strategic questions around the effectiveness of discounts, subscriptions, seasonal trends, and customer engagement strategies.

## Core Business Question:
How can consumer shopping data be leveraged to identify trends, improve customer engagement, and optimize marketing and product strategies?

# Dataset Summary

- 3,900 transactional records across 18 structured variables
- Customer demographics including age, gender, location, and subscription status
- Purchase attributes such as product category, item selection, seasonality, size, color, and purchase amount
- Behavioral indicators including discount usage, promotional activity, purchase frequency, review ratings, and shipping preferences
- Minor missing values in review ratings were addressed during preprocessing to ensure data quality

# Project Deliverables
- Data Preparation & Modeling (Python): Data cleaning, feature engineering, and validation
- Data Analysis (SQL): Business-focused transactional queries and segmentation logic
- Visualization & Insights (Power BI): Interactive dashboards highlighting trends and KPIs
- Documentation & Presentation: Analytical report and executive-style presentation

# Exploratory Data Analysis & Data Preparation (Python)

Data preprocessing and exploration were conducted using Python with a focus on ensuring analytical readiness and consistency.

## Key steps included:
- Importing and inspecting data structure and distributions using pandas
- Generating descriptive statistics to assess trends and anomalies
- Handling missing values through category-based median imputation for review ratings
- Standardizing column naming conventions for clarity
- Feature engineering including demographic age groups and purchase frequency metrics
- Validating redundant promotional fields to maintain clean data design
- Loading the finalized dataset into PostgreSQL for structured SQL analysis

# Data Analysis Using SQL (Business Transactions)

The cleaned dataset was analyzed in PostgreSQL to answer key business questions related to revenue performance, customer behavior, and product trends.

Analysis included:
- Revenue contribution by gender and demographic segments
- Identification of high-spending customers utilizing discounts
- Top-performing products based on customer review ratings
- Purchase value comparison across shipping methods
- Subscriber vs non-subscriber revenue behavior
- Discount dependency across product lines
- Customer segmentation into New, Returning, and Loyal groups
- Best-selling products by category
- Relationship between repeat purchases and subscription adoption
- Revenue distribution across age groups

# Power BI Dashboard & Visual Analytics

An interactive Power BI dashboard was developed to translate analytical results into business-ready insights.

Key features include:
 - Dynamic KPIs for total customers, average purchase value, and review ratings
 - Revenue breakdowns by category and product
 - Customer segmentation visuals
 - Subscription and shipping behavior comparisons
 - Drill-down filters for deeper trend exploration

# Key Results & Insights

 - Male customers accounted for approximately 68% of total revenue contribution
 - Clothing emerged as the highest revenue-generating category
 - Loyal customers represented nearly 80% of the customer base, indicating strong repeat behavior
 - Only 27% of customers were subscribers despite similar average purchase values between subscribers and non-subscribers
 - Express shipping correlated with higher average purchase amounts
 - Several high-performing products demonstrated heavy discount dependency

# Business Recommendations

Based on the analytical findings, several strategic initiatives were identified to improve revenue performance, customer retention, and marketing e^ectiveness.

 - Strengthen Subscription Programs: Introduce exclusive incentives and personalized benefits to increase subscription adoption and recurring revenue.
 - Implement Customer Loyalty Strategies: Develop reward-based programs targeting repeat buyers to transition customers into high-value loyal segments.
 - Optimize Discount Strategies: Reevaluate promotional policies to balance short-term sales growth with long-term profit margins.
 - Enhance Product Positioning: Prioritize the promotion of top-rated and high-performing products across marketing channels to maximize conversion potential.
 - Deploy Targeted Marketing Campaigns: Focus outreach e^orts on high-revenue customer segments and purchasing behaviors to improve campaign e^iciency and ROI.

# Tools & Technologies

 - **Python**: pandas, NumPy for data cleaning and feature engineering
 - **PostgreSQL**: SQL-based business analysis and segmentation
 - **Power BI**: Data modeling, DAX measures, and interactive dashboards
 - **Excel & Word**: Documentation and reporting

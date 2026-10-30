# Customer_Behavior_Analysis
End-to-end customer shopping behavior analysis of 3,900 purchases using Python, PostgreSQL and Power BI: data cleaning, 10 SQL business questions, an interactive dashboard and recommendations.
# Customer Shopping Behavior Analysis

An end-to-end data analytics project that analyzes 3,900 retail purchases to understand spending patterns, customer segments, product preferences and subscription behavior.

## Overview
The dataset has 18 columns covering customer demographics, purchase details and shopping behavior. The workflow has four stages:

1. **Python (pandas):** cleaned the data, filled 37 missing review ratings with the category median, standardized column names, and created an `age_group` feature.
2. **PostgreSQL:** loaded the cleaned data and answered 10 business questions, including revenue by gender and age group, subscriber behavior, discount-dependent products and customer segmentation.
3. **Power BI:** built an interactive dashboard with slicers for subscription status, gender, category and shipping type.
4. **Presentation:** summarized the findings and recommendations for a client audience.

## Key Findings
- Male customers generate about 68% of total revenue.
- Only 27% of customers subscribe, and subscribers spend about the same per purchase ($59.49 vs $59.87).
- 80% of customers are in the Loyal segment.
- Express shipping orders average about 3% more than Standard.
- Young Adults are the highest-revenue age group.

## Recommendations
- Promote exclusive benefits to grow subscriptions.
- Reward repeat buyers to move them into the Loyal segment.
- Review the discount policy to protect margins.
- Highlight top-rated and best-selling products in campaigns.
- Target high-revenue age groups and express-shipping users.

## Tools
Python (pandas, SQLAlchemy) · PostgreSQL · Power BI

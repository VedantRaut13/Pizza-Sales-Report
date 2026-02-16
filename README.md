# Pizza-Sales

Business Case
The objective was to analyze transactional sales data from a pizza business generating $818K in annual revenue to answer key operational questions:

When are peak ordering hours and high-demand days?
Which pizza categories and sizes drive the most revenue?
Are there underperforming products impacting growth?
How can pricing, inventory, and staffing decisions be optimized?
The goal was to transform raw order-level data into a decision-support dashboard for revenue optimization and operational planning.

Analytical Approach
Data Modeling:
Designed a Snowflake schema to ensure scalable relationships between orders, pizzas, categories, and time dimensions.

Data Preparation (ETL):
Cleaned and transformed data using Power Query to standardize dates, categories, and pricing fields.

KPI Development (DAX):
Built key metrics, including:

Total Revenue ($818K)
Average Order Value ($39)
Revenue per Pizza ($17)
Growth %
Peak Hour Orders
Segmentation Analysis:
Analyzed performance by:

Hour of day
Day of week
Month
Category (Classic, Supreme, Chicken, Veggie)
Size (L, M, S, XL)
Security Implementation:
Implemented Row-Level Security (RLS) to enable role-based insights.

Key Insights
Peak demand occurs during evening hours and weekends.
Large-sized pizzas generate the highest revenue contribution.
The classic category leads total revenue contribution.
Some SKUs show high order frequency but low revenue efficiency.
Growth rate indicates short-term decline, signaling an optimization opportunity.
Impact & Business Value
Enabled data-driven staffing decisions based on peak-hour analysis.
Identified high-revenue categories for marketing focus.
Highlighted low-performing products for pricing or bundling strategy.
Provided a centralized executive dashboard for KPI monitoring.
Designed a scalable reporting framework that can support multi-branch expansion.

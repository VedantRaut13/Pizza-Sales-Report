# Pizza-Sales

Business Case:

The objective was to analyze transactional sales data from a pizza business generating $818K in annual revenue to answer key operational questions:

1) When are peak ordering hours and high-demand days?
2) Which pizza categories and sizes drive the most revenue?
3) Are there underperforming products impacting growth?
4) How can pricing, inventory, and staffing decisions be optimized?

The goal was to transform raw order-level data into a decision-support dashboard for revenue optimization and operational planning.

Analytical Approach:

Data Modeling:
* Designed a Snowflake schema to ensure scalable relationships between orders, pizzas, categories, and time dimensions.

Data Preparation (ETL):
* Cleaned and transformed data using Power Query to standardize dates, categories, and pricing fields.

KPI Development (DAX):
* Built key metrics, including:

1) Total Revenue ($818K)
2) Average Order Value ($39)
3) Revenue per Pizza ($17)
4) Growth %
5)cPeak Hour Orders

Segmentation Analysis:
* Analyzed performance by:

1) Hour of day
2) Day of week
3) Month
4) Category (Classic, Supreme, Chicken, Veggie)
5) Size (L, M, S, XL)

Security Implementation:

* Implemented Row-Level Security (RLS) to enable role-based insights.

Key Insights: 

1) Peak demand occurs during evening hours and weekends.
2) Large-sized pizzas generate the highest revenue contribution.
3) The classic category leads total revenue contribution.
4) Some SKUs show high order frequency but low revenue efficiency.
5) Growth rate indicates short-term decline, signaling an optimization opportunity.

Impact & Business Value :

1) Enabled data-driven staffing decisions based on peak-hour analysis.
2) Identified high-revenue categories for marketing focus.
3) Highlighted low-performing products for pricing or bundling strategy.
4) Provided a centralized executive dashboard for KPI monitoring.
5) Designed a scalable reporting framework that can support multi-branch expansion.

<img width="1281" height="718" alt="Screenshot 2026-02-15 171158" src="https://github.com/user-attachments/assets/0f3eb502-d8f8-4dd4-a0c2-3dbb1ef062b5" />
<img width="1325" height="731" alt="Screenshot 2026-02-15 171305" src="https://github.com/user-attachments/assets/23c41785-f14f-4dae-bbd3-49de00c18bfb" />
<img width="1308" height="735" alt="Screenshot 2026-02-15 171334" src="https://github.com/user-attachments/assets/c82b0748-1778-4f87-b096-a871a215ed14" />
<img width="1310" height="726" alt="Screenshot 2026-02-15 171353" src="https://github.com/user-attachments/assets/940e771b-f301-4351-bc71-d70469d5c3f9" />




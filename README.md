# egotm-final-stage-interview-dashboard
Power BI dashboard and supporting SQL queries analysing website traffic, conversion rates, marketing channels, revenue performance, and product sales using OperationsDb dataset.
Latin Toys – Business Intelligence Dashboard

This project presents a two-page Power BI dashboard supported by SQL queries designed to analyse operational and marketing performance using data from an assumed SQL Server database named OperationsDb.
The dashboard answers key business questions such as:
- What is the trend in website sessions and order volume?
- How has the session-to-order conversion rate changed over time?
- Which marketing channels generate the most revenue and orders?
- How has revenue per order and revenue per session evolved?
- Which products generate the highest and lowest sales?
- What is the refund impact by product?

Key Metrics Included:
- Total Sessions
- Total Orders
- Conversion Rate
- Total Revenue
- Net Revenue
- Revenue per Order
- Revenue per Session
- Refund Value

Dashboard Structure
Page 1 – Overall Performance
Focuses on:
- Monthly session and order trends
- Conversion rate trend
- Revenue trend
- Refund analysis
- Product performance

Page 2 – Channel Performance
Focuses on:
- Orders by marketing channel
- Revenue by channel
- Conversion rate by channel
- Channel comparison over time

SQL Analysis
The repository includes simple .sql files that demonstrate how key KPIs and trends can be calculated directly from SQL Server before being visualised in Power BI.
The queries use:
- GROUP BY
- SUM()
- COUNT()
- DISTINCTCOUNT
- Calculated metrics (e.g., conversion rate)
- Aggregation for product and channel analysis

Tools Used
- Power BI
- SQL Server (Assumed database: OperationsDb)
- DAX Measures
- Time Intelligence Functions

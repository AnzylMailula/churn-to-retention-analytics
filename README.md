# Telecom Customer Retention — Decision Brief

Diagnosed why 22.57% of subscribers churn, built a validated risk-scoring 
model to flag who's next, and sized the opportunity in dollars not just 
charts.

[Read the full Decision Brief →](./Customer%20retention%20decision%20brief.md)

<img width="573" height="320" alt="Screenshot 2026-07-30 171001" src="https://github.com/user-attachments/assets/d8f4d382-9533-4774-912e-4741698333c8" />


## Key Numbers

- **$1.34M/month** estimated recoverable revenue if top recommendations land
- **22.57%** baseline churn rate
- **29% → 11%** churn drop as subscriber tenure increases
- **40% vs 21%** churn gap between 1-star and 5-star satisfaction ratings

## Tools

Power BI (data modeling, DAX) · SQL Server / SSMS (T-SQL, views, CTEs) 

## Methodology

Baseline churn rate → segment every attribute → compare each segment against 
baseline → flag gaps of 5+ percentage points or 1.5x baseline as real signal 
→ rank by business impact → visualize. Every major finding was independently 
reproduced in SQL to confirm it holds regardless of tool. Findings that 
didn't clear the threshold are documented as ruled out, not omitted — see 
the decision brief.

## Repo Structure

- [Customer Retention Decision Brief.md](./Customer%20Retention%20Decision%20Brief.md) — full findings, recommendations, financial impact
- [Power BI and SQL Analytical Traceability.md](./Power%20BI%20and%20SQL%20Analytical%20Traceability.md) — full Power BI + DAX + SQL methodology, step by step

## Notes on the dashboard

Every visual is sourced from SQL-validated static tables rather than a live 
model connection the underlying analysis is fully cross-checked in SQL 
Server; see `Power BI and SQL Analytical Traceability.md ` for the source queries.


Built by Anzyl · [https://za.linkedin.com/in/anzylmailula] · [andzelgracious804@gmail.com]

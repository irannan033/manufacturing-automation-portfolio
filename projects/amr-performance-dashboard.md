# AMR Fleet Performance Dashboard

**Focus:** Operational analytics · Fleet monitoring  
**Tools:** PostgreSQL, SQL, Power BI

## Objective
Provide a clearer view of fleet performance by turning operational database records into a dashboard for monitoring robot runtime, online time, and utilization trends.

## Work and design scope
- Query operational data from PostgreSQL.
- Filter fleet records by robot identifier and reporting period.
- Prepare daily and monthly utilization summaries.
- Visualize runtime and online-time patterns in Power BI.
- Keep the dashboard structure reusable across factory environments where database configuration differs.

## Potential value
A consistent dashboard can help teams compare fleet usage, identify unusual changes, and prioritize follow-up investigation. Any operational KPI should be validated against the source system and agreed calculation rules before it is used for reporting.

*This page describes the dashboard workstream and intended monitoring approach; it does not claim a public or production deployment beyond the user's verified project context.*

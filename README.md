# Netflix | Global Business Intelligence Suite (Power BI)

**by Soham S. Amburle**

## Project Overview

This project simulates an **enterprise-grade Business Intelligence solution** for a global streaming platform similar to Netflix, built using **Power BI** and a large-scale **synthetic streaming dataset**.

The objective is to demonstrate how executive leadership, product teams, content strategists, marketing departments, and regional market analysts can use data-driven dashboards to monitor **subscriber growth, viewing behavior, content performance, revenue streams, user engagement, and global market expansion**.

The solution is designed as a **15-dashboard enterprise analytics suite**, similar to real-world BI platforms used in global streaming companies.

---

## Dashboard Suite Structure

1. Executive Overview
2. Global Subscriber Overview
3. Regional Market Analysis
4. Revenue Analytics
5. Subscription Plan Performance
6. Customer Demographics
7. Watch Behavior Analysis
8. Device Usage Analytics
9. Binge Watching Analysis
10. Content Performance
11. Genre Analytics
12. Viewer Ratings Analysis
13. Content Production Insights
14. Customer Churn Analysis
15. Global Streaming Insights

---

## Key Business Areas Covered

* Executive KPI monitoring & strategic performance
* Global subscriber acquisition and growth tracking
* Regional market performance comparison
* Subscription plan adoption and revenue contribution
* User demographic insights and audience segmentation
* Viewing behavior and watch-time analytics
* Device usage distribution across platforms
* Binge-watching patterns and engagement metrics
* Content performance and audience engagement
* Genre popularity trends across regions
* Viewer ratings and audience feedback analysis
* Content production trends by language and country
* Customer churn and retention analytics
* Strategic global streaming insights

---

## Dataset

* **Dataset Size:** ~200,000 synthetic records
* **Data Structure:** Snowflake schema architecture
* **Time Period:** Simulated multi-year streaming activity

The dataset is fully synthetic and does **not** contain any real Netflix data. It is intended strictly for **analytics, visualization, and portfolio demonstration purposes**.

---

## Data Model Structure

### Fact Tables (Event-Level Data)

1. **Watch History** – User viewing sessions and watch duration
2. **Subscriptions** – Subscriber lifecycle and plan information
3. **Ratings** – User ratings and content feedback

### Dimension Tables (Descriptive Data)

**User & Customer Dimensions**

* Users (age, gender, signup details)

**Content Dimensions**

* Content (movies & series catalog)
* Genre
* Language

**Platform Dimensions**

* Devices (mobile, smart TV, tablet, desktop)

**Geographic Dimensions**

* Geography (country, region, continent)

**Subscription Dimensions**

* Subscription Plans (Basic, Standard, Premium)

**Time Dimensions**

* Date / Month / Quarter / Year

---

## Dataset Tables Overview

### Fact Tables

1. Fact_WatchHistory
2. Fact_Subscriptions
3. Fact_Ratings

### Dimension Tables

4. Dim_Users
5. Dim_Content
6. Dim_Genre
7. Dim_Language
8. Dim_Geography
9. Dim_Device
10. Dim_SubscriptionPlan
11. Dim_Time

---

## Data Model Design

* **Snowflake schema architecture**
* Event-based fact tables for streaming activity
* Dimension tables for content, geography, and user attributes
* Advanced DAX measures for KPI calculations
* Hierarchical drill-down (Global → Continent → Country → Content → User behavior)
* Cross-filtering and interactive dashboard navigation

---

## Tools & Technologies

* Power BI Desktop
* DAX (advanced KPIs and time intelligence)
* Data Modeling (Snowflake schema design)
* Synthetic data generation (Python / Excel)
* Interactive dashboard design and storytelling

---

## Project Goals

* Demonstrate enterprise-level BI architecture for streaming analytics
* Showcase advanced Power BI dashboard development
* Build executive-ready dashboards aligned with data-driven decision-making
* Simulate real-world analytics used by global streaming platforms
* Deliver deep insights into user engagement, content performance, and global market trends

---

## Disclaimer

This project is **not affiliated with Netflix**.
All data is synthetic and created solely for **educational and portfolio purposes**.

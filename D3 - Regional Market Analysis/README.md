# Netflix Global Streaming Intelligence Suite – Regional Market Analysis

**Organization:** Netflix (Simulated Global Streaming Platform Model)  
**Tool:** Power BI  
**Dataset:** Synthetic Global Streaming Dataset – 2,394 Records  
**Dashboard Focus:** Regional Market Performance, Subscriber Distribution, Revenue Trends, and Engagement Patterns  
**Date:** 12 March 2026  
**Created by:** Soham S. Amburle  

---

## Overview

The **Regional Market Analysis Dashboard** provides a strategic view of how a global streaming platform performs across different geographic markets. Built using a synthetic dataset inspired by Netflix’s global analytics environment, the dashboard highlights **regional subscriber distribution, revenue performance, subscription plan adoption, and viewer engagement levels**.

This dashboard enables analysts and decision-makers to identify **which continents and regions contribute the most subscribers and revenue**, while also understanding how user engagement varies geographically.

By combining KPI indicators, regional comparison charts, subscription plan breakdowns, and interactive slicers, the dashboard provides a **clear analytical perspective on global market performance and growth opportunities**.

Key analytical questions addressed by this dashboard include:

- Which continents and regions have the largest subscriber base?
- How does revenue performance vary across geographic markets?
- Which subscription plans dominate different regions?
- Which regions generate the highest viewer engagement through watch hours?
- How broad is the platform’s global market reach?

Through these insights, the dashboard helps simulate the type of **regional intelligence used by global streaming companies to guide market expansion strategies**.

---

## Business Storyline & Analytical Flow

### 1. Regional KPI Snapshot – KPI Cards

Seven KPI cards provide a quick overview of the platform’s regional footprint:

- **Total Subscribers**
- **Total Revenue**
- **Active Subscribers**
- **Cancelled Subscriptions**
- **Average Revenue Per User (ARPU)**
- **Total Watch Hours**
- **Total Countries**

These indicators provide an immediate understanding of **platform scale, geographic reach, and engagement levels**.

---

### 2. Strategic Regional Visualizations

Four major visuals help compare market performance across regions:

1. **SUBSCRIBERS BY CONTINENT** – Area Chart  
   Displays subscriber distribution across continents.

2. **REVENUE BY REGION** – Clustered Bar Chart  
   Compares revenue performance across regions.

3. **SUBSCRIPTION PLAN DISTRIBUTION BY REGION** – Stacked Column Chart  
   Shows how Basic, Standard, and Premium plans are adopted in different markets.

4. **WATCH HOURS BY REGION** – Clustered Column Chart  
   Highlights which regions generate the highest viewing engagement.

---

### 3. Interactive Slicers

Six slicers allow users to dynamically filter regional analysis:

- Continent (`Dim_Geography[Continent]`)
- Region (`Dim_Geography[Region]`)
- Country (`Dim_Geography[Country]`)
- Subscription Plan (`Dim_SubscriptionPlan[PlanName]`)
- Year (`Dim_Time[Year]`)
- Content Type (`Dim_Content[ContentType]`)

These filters enable flexible exploration of market performance across **geography, time, subscription tiers, and content categories**.

---

### 4. Gauge

- **REGIONAL SUBSCRIBER TARGET** – Gauge visualization showing current subscribers against a simulated growth target.

This visual provides a quick view of whether the platform is meeting **regional expansion goals**.

---

## Key Takeaways

This dashboard allows stakeholders to:

- Identify high-performing regions in terms of subscribers and revenue
- Compare viewer engagement levels across geographic markets
- Evaluate subscription plan adoption patterns by region
- Monitor regional growth relative to target benchmarks
- Understand the global footprint of the streaming platform

Overall, the dashboard provides a **concise regional intelligence layer** within the Global Streaming Intelligence Suite.

---

## Tools & Data

- **Visualization Tool:** Power BI  
- **Dataset:** Synthetic global streaming analytics dataset  
- **Record Count:** ~2,394 rows across all tables  
- **Time Period:** Simulated multi-year streaming activity  
- **Model Design:** Snowflake Schema  

### Tables Used

**Fact Tables**
- Fact_WatchHistory
- Fact_Subscriptions
- Fact_Ratings

**Dimension Tables**
- Dim_Users
- Dim_Content
- Dim_Time
- Dim_Geography
- Dim_Genre
- Dim_Language
- Dim_Device
- Dim_SubscriptionPlan

The dataset was generated using **Mockaroo** to simulate realistic streaming analytics scenarios including global subscribers, viewing behavior, subscription plans, and content consumption patterns.

---

> **Note:** This project is not affiliated with Netflix. All data used in this dashboard is synthetic and created solely for learning, analysis, and portfolio demonstration purposes.

---

**Dashboard and Documentation by SOHAM S. AMBURLE**  
**12 March 2026**

# Global Streaming Intelligence Suite – Global Subscriber Overview

**Organization:** Netflix (Simulated Global Streaming Platform Model)  
**Tool:** Power BI  
**Dataset:** Synthetic Global Streaming Platform Dataset – ~2,394 Records  
**Dashboard Focus:** Global Subscriber Distribution and Subscription Plan Adoption  
**Date:** 12 March 2026  
**Created by:** Soham S. Amburle  

---

## Overview

The **Global Subscriber Overview Dashboard** provides a high-level view of how subscribers are distributed across a simulated global streaming platform inspired by Netflix.

Built in **Power BI** using a synthetic dataset structured with a **Snowflake Schema**, this dashboard enables analysts and stakeholders to understand the **size of the subscriber base, global distribution of users, and subscription plan adoption patterns**.

The dashboard acts as one of the core analytical pages in the **Global Streaming Intelligence Suite**, offering insights into the platform’s geographic reach and subscriber composition.

The dashboard helps answer key questions such as:

- Where are most subscribers located globally?
- Which continents and regions contribute the largest subscriber base?
- Which subscription plans are most popular among users?
- What proportion of subscriptions are active versus cancelled?

By combining **KPI indicators, geographic visualizations, and interactive filters**, the dashboard provides a concise overview of global subscriber distribution.

---

## Business Storyline & Analytical Flow

The dashboard follows a structured analytical flow that moves from **high-level subscriber metrics to geographic distribution insights**.

### 1. Subscriber KPI Snapshot

Seven KPI cards provide a quick summary of the platform’s subscriber ecosystem:

- **Total Subscribers**
- **Total Countries**
- **Active Subscribers**
- **Cancelled Subscribers**
- **Average Subscription Price**
- **Total Subscriptions**
- **Subscribers per Country**

These KPIs help users quickly understand the **scale of the platform and subscriber distribution characteristics**.

---

### 2. Geographic Distribution Analysis

The dashboard then explores **how subscribers are distributed geographically** across the platform.

Four key visuals support this analysis:

1. **Subscribers by Continent** – Clustered Column Chart  
2. **Subscribers by Region** – Area Chart  
3. **Subscribers by Country** – Filled Map  
4. **Subscribers by Subscription Plan** – Donut Chart  

These visuals allow users to identify:

- High-performing geographic markets
- Regions with strong platform adoption
- Distribution of subscribers across pricing tiers

---

### 3. Interactive Slicers

Seven slicers allow users to dynamically filter the dashboard across multiple dimensions:

- Continent (`Dim_Geography[Continent]`)
- Region (`Dim_Geography[Region]`)
- Country (`Dim_Geography[Country]`)
- Subscription Plan (`Dim_SubscriptionPlan[PlanName]`)
- Year (`Dim_Time[Year]`)
- Subscription Status (`Fact_Subscriptions[Status]`)
- Genre (`Dim_Genre[GenreName]`)

These filters enable flexible exploration of subscriber patterns across **geographic levels, subscription tiers, and content categories**.

---

## Key Takeaways

This dashboard helps analysts and stakeholders:

- Understand the **global scale of the subscriber base**
- Identify **key geographic markets with high subscriber adoption**
- Evaluate **subscription plan popularity**
- Track **active versus cancelled subscription levels**
- Explore subscriber distribution across **continents, regions, and countries**

The dashboard acts as an important **subscriber intelligence view** within the overall streaming analytics platform.

---

## Tools & Data

- **Visualization Tool:** Power BI  
- **Dataset:** Synthetic global streaming platform dataset  
- **Total Records:** ~2,394 rows across all tables  
- **Data Model:** Snowflake Schema  

### Fact Tables
- Fact_WatchHistory
- Fact_Subscriptions
- Fact_Ratings

### Dimension Tables
- Dim_Users
- Dim_Content
- Dim_Time
- Dim_Geography
- Dim_Genre
- Dim_Language
- Dim_Device
- Dim_SubscriptionPlan

The dataset was generated using **Mockaroo** to simulate real-world streaming analytics scenarios such as **global subscriber distribution, subscription plans, content genres, and viewing behavior**.

---

> **Note:** This project is not affiliated with Netflix. All data used in this dashboard is synthetic and created solely for learning, analysis, and portfolio demonstration purposes.

---

**Dashboard and Documentation by SOHAM S. AMBURLE**  
**12 March 2026**

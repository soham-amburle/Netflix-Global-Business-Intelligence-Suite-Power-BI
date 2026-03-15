# Netflix Global Streaming Intelligence Suite – Global Subscriber Overview

**Organization:** Netflix (Simulated Global Streaming Platform Model)  
**Tool:** Power BI  
**Dataset:** Synthetic Global Streaming Dataset – 2,394 Records  
**Dashboard Focus:** Global Subscriber Distribution and Subscription Insights  
**Date:** 11 March 2026  
**Created by:** Soham S. Amburle  

---

## Overview

The **Global Subscriber Overview Dashboard** provides a high-level analytical view of subscriber distribution across global markets for a streaming platform model inspired by Netflix. Built using a synthetic dataset consisting of 2,394 records, the dashboard enables stakeholders to evaluate how subscribers are distributed geographically and across subscription plans.

The dashboard focuses on understanding **global subscriber footprint, market penetration, subscription plan adoption, and subscriber concentration by region and country**. By combining KPI indicators, geographic visualizations, and subscription plan analysis, the dashboard offers a clear and concise overview of the platform's subscriber base.

This dashboard answers several strategic questions:

- How many subscribers does the platform currently have?
- How are subscribers distributed across continents, regions, and countries?
- Which markets have the highest subscriber concentration?
- What is the adoption distribution of subscription plans?
- What is the balance between active and cancelled subscriptions?

Through KPI cards, geographic mapping, interactive slicers, and distribution charts, this dashboard provides a **clear operational view of global subscriber presence**.

---

## Business Storyline & Analytical Flow

### 1. Subscriber KPI Snapshot – KPI Cards

Seven KPI cards provide a quick summary of global subscriber metrics:

- **Total Subscribers**
- **Total Countries**
- **Active Subscribers**
- **Cancelled Subscribers**
- **Average Subscription Price**
- **Total Subscriptions**
- **Subscribers per Country**

These KPIs allow stakeholders to quickly assess the **scale, distribution, and status of the subscriber base**.

---

### 2. Global Subscriber Distribution Visuals

Four key visuals provide insights into how subscribers are distributed globally:

1. **SUBSCRIBERS BY CONTINENT** – Clustered Column Chart  
2. **SUBSCRIBERS BY COUNTRY** – Filled Map Visualization  
3. **SUBSCRIBERS BY SUBSCRIPTION PLAN** – Donut Chart  
4. **SUBSCRIBERS BY REGION** – Area Chart  

These visuals help identify **regional concentration, country-level market penetration, and subscription plan adoption patterns**.

---

### 3. Interactive Slicers

Seven slicers allow dynamic filtering across multiple dimensions:

- Continent (`Dim_Geography[Continent]`)
- Region (`Dim_Geography[Region]`)
- Country (`Dim_Geography[Country]`)
- Subscription Plan (`Dim_SubscriptionPlan[PlanName]`)
- Year (`Dim_Time[Year]`)
- Subscription Status (`Fact_Subscriptions[Status]`)
- Genre (`Dim_Genre[GenreName]`)

These filters allow analysts to explore **subscriber patterns across geography, subscription types, and time dimensions**.

---

## Key Insights Enabled by the Dashboard

The dashboard enables analysts and stakeholders to:

- Monitor the global scale of the subscriber base
- Identify high-performing regions and markets
- Evaluate subscription plan adoption trends
- Compare active and cancelled subscription levels
- Assess geographic distribution of platform users

---

## Tools & Data

- **Visualization Tool:** Power BI  
- **Dataset:** Synthetic streaming platform dataset  
- **Record Count:** 2,394 records across all tables  
- **Model Design:** Snowflake Schema  
- **Purpose:** Business Intelligence portfolio project simulating streaming analytics  

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

---

## Data Disclaimer

This dashboard is built using a **synthetic dataset (~2,394 records)** generated for analytical and demonstration purposes. The data simulates a global streaming platform environment and does **not represent real user or business data**.

The dataset follows a **snowflake schema data model** and includes fact tables (Fact_WatchHistory, Fact_Subscriptions, Fact_Ratings) and multiple dimension tables (Dim_Users, Dim_Content, Dim_Time, Dim_Geography, Dim_Genre, Dim_Language, Dim_Device, Dim_SubscriptionPlan).

The data was generated using **Mockaroo** to replicate typical streaming analytics scenarios such as subscriber distribution, subscription plans, device usage, and global viewing patterns.

---

> **Note:** This project is not affiliated with Netflix. All data used in this dashboard is synthetic and created solely for learning, analysis, and portfolio demonstration purposes.

---

**Dashboard and Documentation by SOHAM S. AMBURLE**  
**11 March 2026**

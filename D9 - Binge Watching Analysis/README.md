# Global Streaming Intelligence Suite – Binge Watching Analysis

**Organization:** Netflix (Simulated Streaming Analytics Model)
**Tool:** Power BI
**Dataset:** Synthetic Global Streaming Dataset – 2,394 Records
**Dashboard Focus:** Binge Watching Behavior, Session Patterns, and Engagement Analysis
**Date:** 18 March 2026
**Created by:** Soham S. Amburle

---

## Overview

The **Binge Watching Analysis Dashboard** provides a focused view of user viewing behavior by identifying binge-watching patterns across a global streaming platform.

Built using a synthetic dataset of 2,394 records and a snowflake schema data model, this dashboard enables analysts to understand **long viewing sessions, user engagement intensity, and content consumption behavior**.

This dashboard answers key analytical questions:

* How frequently do users engage in binge watching?
* What proportion of sessions are binge vs normal?
* Which devices and genres drive binge watching?
* How does binge behavior vary across content types?
* What is the average engagement level per session?

Through KPI cards, charts, and slicers, the dashboard provides an **interactive and behavior-focused analysis of streaming engagement**.

---

## Business Storyline & Analytical Flow

### 1. Binge KPI Snapshot – KPI Cards

Six KPI cards provide a quick overview of binge behavior:

* **Total Watch Hours**
* **Total Sessions**
* **Average Watch Time per Session**
* **Sessions per User**
* **Binge Sessions**
* **Binge Rate (%)**

These KPIs help stakeholders quickly assess **engagement intensity and binge behavior trends**.

---

### 2. Main Analytical Visuals

Four key visuals provide binge behavior insights:

1. **BINGE VS NORMAL SESSIONS** – Donut Chart (Unit: Sessions %)
2. **BINGE SESSIONS BY DEVICE** – Clustered Bar Chart (Unit: Sessions)
3. **BINGE SESSIONS BY GENRE** – Clustered Bar Chart (Unit: Sessions)
4. **BINGE SESSIONS BY CONTENT TYPE** – Donut Chart (Unit: Sessions %)

These visuals highlight **where binge watching occurs and what drives it**.

---

### 3. Interactive Slicers

Eight slicers allow dynamic filtering:

* Device Type (`Dim_Device[DeviceType]`)
* Continent (`Dim_Geography[Continent]`)
* Country (`Dim_Geography[Country]`)
* Content Type (`Dim_Content[ContentType]`)
* Genre (`Dim_Genre[GenreName]`)
* Subscription Plan (`Dim_SubscriptionPlan[PlanName]`)
* Language (`Dim_Language[LanguageName]`)
* Age Group (`Dim_Users[Age Group]`)

These slicers enable exploration of binge patterns across **devices, content, geography, and demographics**.

---

## Key Takeaways

This dashboard enables stakeholders to:

* Identify binge-watching trends and session behavior
* Compare binge vs normal viewing patterns
* Analyze engagement intensity across users
* Understand how devices and genres influence binge watching
* Explore content consumption patterns across different segments

---

## Tools & Data

* **Visualization Tool:** Power BI
* **Dataset:** Synthetic global streaming dataset
* **Record Count:** ~2,394 rows
* **Data Model:** Snowflake Schema
* **Purpose:** Binge behavior analytics for streaming platform BI portfolio

---

> **Note:** This project is not affiliated with Netflix. All data used in this dashboard is synthetic and created solely for learning, analysis, and portfolio demonstration purposes.

---

**Dashboard and Documentation by SOHAM S. AMBURLE**
**18 March 2026**

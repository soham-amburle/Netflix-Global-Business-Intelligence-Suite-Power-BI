# Netflix | Content Performance Dashboard

**Organization:** Netflix (Simulated Global Streaming Platform)  
**Tool:** Power BI  
**Dataset:** Synthetic Global Streaming Dataset – ~200,000 Records  
**Dashboard Focus:** Content Performance, Viewer Engagement, Watch Behavior, and Ratings Analysis  
**Date:** 19 March 2026  
**Created by:** Soham S. Amburle  

---

## Overview

The **Content Performance Dashboard** provides a comprehensive view of how content performs on a global streaming platform. Built using a large-scale synthetic dataset, this dashboard enables analysts and decision-makers to evaluate **viewer engagement, content popularity, watch-time distribution, and audience feedback through ratings**.

The dashboard focuses on answering key business questions related to content consumption, helping stakeholders understand which titles, genres, and formats drive the highest engagement.

This dashboard answers key questions such as:

- Which content titles generate the highest watch hours?  
- What genres drive the most viewer engagement?  
- How do movies and series compare in performance?  
- Which content receives the highest audience ratings?  
- What is the overall completion behavior of viewers?  

Through KPI cards, interactive slicers, and performance-driven visuals, the dashboard delivers an **insight-rich view of content success and audience engagement patterns**.

---

## Business Storyline & Analytical Flow

### 1. Content Performance Snapshot – KPI Cards

Seven KPI cards provide a high-level summary of content engagement:

- **Total Watch Hours**  
- **Total Streams**  
- **Unique Viewers**  
- **Average Watch Time (Minutes)**  
- **Completion Rate (%)**  
- **Average Rating**  
- **Total Content Titles**  

These KPIs provide a **quick overview of platform engagement and content performance health**.

---

### 2. Core Performance Visuals

Four key visuals highlight content performance across different dimensions:

1. **TOP 10 CONTENT BY WATCH HOURS** – Bar Chart (Unit: Hours)  
2. **WATCH HOURS BY GENRE** – Column Chart (Unit: Hours)  
3. **WATCH HOURS BY CONTENT TYPE** – Donut Chart (%)  
4. **TOP 10 CONTENT BY AVG RATING** – Bar Chart (Rating Score)  

These visuals help identify **top-performing content, genre trends, and audience preferences**.

---

### 3. Interactive Slicers

Seven slicers allow dynamic filtering across multiple dimensions:

- Content Type (`Dim_Content[ContentType]`)  
- Genre (`Dim_Genre[GenreName]`)  
- Language (`Dim_Language[LanguageName]`)  
- Release Year (`Dim_Content[ReleaseYear]`)  
- Country (`Dim_Geography[Country]`)  
- Date (`Dim_Time[Date]`)  
- Device Type (`Dim_Device[DeviceType]`)  

These slicers enable users to explore content performance across **regions, devices, time periods, and audience preferences**.

---

## Key Takeaways

This dashboard enables stakeholders to:

- Identify top-performing content based on watch hours  
- Understand genre-level engagement trends  
- Compare performance between movies and series  
- Analyze audience ratings and feedback  
- Evaluate viewer completion behavior  
- Explore content performance across regions and devices  

---

## Tools & Data

- **Visualization Tool:** Power BI  
- **Dataset:** Fully synthetic global streaming dataset  
- **Record Count:** ~200,000 records  
- **Time Period:** Simulated multi-year streaming activity  
- **Data Model:** Snowflake Schema (Fact_WatchHistory, Fact_Subscriptions, Fact_Ratings with multiple dimension tables)  
- **Purpose:** Content analytics dashboard for portfolio demonstration  

---

> **Note:** This project is not affiliated with Netflix. All data used in this dashboard is synthetic and created solely for learning, analysis, and portfolio demonstration purposes.

---

**Dashboard and Documentation by SOHAM S. AMBURLE**  
**19 March 2026**

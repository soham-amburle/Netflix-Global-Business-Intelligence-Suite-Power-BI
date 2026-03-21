# Global Streaming Intelligence Suite – Genre Analytics

**Organization:** Netflix (Simulated Streaming Analytics Model)  
**Tool:** Power BI  
**Dataset:** Synthetic Global Streaming Dataset – ~2,394 Records  
**Dashboard Focus:** Genre Performance, Engagement Trends, and Viewer Preferences  
**Date:** 20 March 2026  
**Created by:** Soham S. Amburle  

---

## Overview

The **Genre Analytics Dashboard** provides a comprehensive analysis of how different content genres perform on a global streaming platform.

Built using a synthetic dataset and a snowflake schema data model, this dashboard enables analysts to understand **genre popularity, viewer engagement, and content consumption patterns across categories**.

This dashboard answers key analytical questions:

* Which genres generate the highest watch hours?
* Which genres are most frequently streamed?
* How do viewer ratings vary across genres?
* How is engagement distributed across content types within each genre?
* Which genres drive the highest audience engagement?

Through KPI cards, charts, and slicers, the dashboard delivers an **interactive and genre-focused analysis of content consumption**.

---

## Business Storyline & Analytical Flow

### 1. Genre Performance Snapshot – KPI Cards

Seven KPI cards provide a quick overview:

* **Genre Watch Hours**
* **Genre Streams**
* **Genre Viewers**
* **Avg Watch Time**
* **Genre Completion %**
* **Avg Genre Rating**
* **Genre Titles**

These KPIs help stakeholders quickly assess **genre-level engagement, scale, and performance**.

---

### 2. Main Analytical Visuals

Four visuals provide deeper genre insights:

1. **WATCH HOURS BY GENRE** – Clustered Bar Chart (Unit: Hours)  
2. **TOP 5 GENRES BY STREAMS** – Clustered Column Chart (Unit: Streams)  
3. **AVG RATING BY GENRE** – Area Chart (Unit: Rating Score)  
4. **GENRE DISTRIBUTION BY CONTENT TYPE** – Stacked Bar Chart (Unit: Hours)  

These visuals highlight **genre popularity, engagement patterns, and content mix distribution**.

---

### 3. Interactive Slicers

Eight slicers enable dynamic filtering:

* Genre (`Dim_Genre[GenreName]`)
* Content Type (`Dim_Content[ContentType]`)
* Language (`Dim_Language[LanguageName]`)
* Country (`Dim_Geography[Country]`)
* Continent (`Dim_Geography[Continent]`)
* Date (`Dim_Time[Date]`)
* Device Type (`Dim_Device[DeviceType]`)
* Release Year (`Dim_Content[ReleaseYear]`)

These slicers allow exploration across **content attributes, geography, time, and platform usage**.

---

## Key Takeaways

This dashboard enables stakeholders to:

* Identify top-performing genres driving engagement  
* Understand audience preferences across content categories  
* Evaluate genre quality using viewer ratings  
* Analyze how content types contribute within each genre  
* Support content strategy and genre-based investment decisions  

---

## Tools & Data

* **Visualization Tool:** Power BI  
* **Dataset:** Synthetic global streaming dataset  
* **Record Count:** ~2,394 rows  
* **Data Model:** Snowflake Schema  
* **Purpose:** Genre performance analytics for BI portfolio  

---

> **Note:** This project is not affiliated with Netflix. All data is synthetic and created solely for educational and portfolio purposes.

---

**Dashboard and Documentation by SOHAM S. AMBURLE**  
**20 March 2026**

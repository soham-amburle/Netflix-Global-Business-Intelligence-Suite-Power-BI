# Global Streaming Intelligence Suite – Content Production Insights

**Organization:** Netflix (Simulated Streaming Analytics Model)  
**Tool:** Power BI  
**Dataset:** Synthetic Global Streaming Dataset – ~2,394 Records  
**Dashboard Focus:** Content Production Trends, Distribution, and Catalog Insights  
**Date:** 22 March 2026  
**Created by:** Soham S. Amburle  

---

## Overview

The **Content Production Insights Dashboard** provides a comprehensive analysis of content creation trends and catalog distribution across a global streaming platform.

Built using a synthetic dataset and a snowflake schema data model, this dashboard enables analysts to understand **how content is produced across countries, languages, genres, and time**.

This dashboard answers key analytical questions:

* How has content production evolved over time?
* Which countries produce the most content?
* What genres dominate the content catalog?
* How is content distributed across languages?
* What is the proportion of movies vs series?

Through KPI cards, charts, and slicers, the dashboard delivers an **interactive and production-focused view of the streaming content ecosystem**.

---

## Business Storyline & Analytical Flow

### 1. Content Production Snapshot – KPI Cards

Eight KPI cards provide a high-level overview:

* **Total Titles**
* **Avg Release Year**
* **Total Genres**
* **Total Languages**
* **Prod Countries**
* **Avg Duration (Min)**
* **Movies %**
* **Series %**

These KPIs help stakeholders quickly assess **catalog size, diversity, and production trends**.

---

### 2. Main Analytical Visuals

Five visuals provide deeper production insights:

1. **CONTENT RELEASE TREND** – Line Chart (Unit: Titles)  
2. **CONTENT BY PRODUCTION COUNTRY** – Map (Unit: Titles)  
3. **CONTENT DISTRIBUTION BY GENRE** – Bar Chart (Unit: Titles)  
4. **CONTENT BY LANGUAGE** – Column Chart (Unit: Titles)  
5. **CONTENT TYPE DISTRIBUTION** – Donut Chart (Unit: %)  

These visuals highlight **production growth, geographic distribution, and catalog composition**.

---

### 3. Interactive Slicers

Eight slicers enable dynamic filtering:

* Content Type (`Dim_Content[ContentType]`)
* Genre (`Dim_Genre[GenreName]`)
* Language (`Dim_Language[LanguageName]`)
* Production Country (`Dim_Content[ProductionCountryID]`)
* Release Year (`Dim_Content[ReleaseYear]`)
* Date (`Dim_Time[Date]`)
* Continent (`Dim_Geography[Continent]`)
* Country (`Dim_Geography[Country]`)

These slicers allow exploration across **content attributes, geography, and time**.

---

## Key Takeaways

This dashboard enables stakeholders to:

* Analyze content production trends over time  
* Identify leading content-producing countries  
* Understand catalog diversity across genres and languages  
* Evaluate content mix between movies and series  
* Support strategic decisions for content investment and expansion  

---

## Tools & Data

* **Visualization Tool:** Power BI  
* **Dataset:** Synthetic global streaming dataset  
* **Record Count:** ~2,394 rows  
* **Data Model:** Snowflake Schema  
* **Purpose:** Content production analytics for BI portfolio  

---

> **Note:** This project is not affiliated with Netflix. All data is synthetic and created solely for educational and portfolio purposes.

---

**Dashboard and Documentation by SOHAM S. AMBURLE**  
**22 March 2026**

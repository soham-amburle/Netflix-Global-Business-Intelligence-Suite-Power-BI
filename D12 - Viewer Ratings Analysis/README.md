# Global Streaming Intelligence Suite – Viewer Ratings Analysis

**Organization:** Netflix (Simulated Streaming Analytics Model)  
**Tool:** Power BI  
**Dataset:** Synthetic Global Streaming Dataset – ~2,394 Records  
**Dashboard Focus:** Viewer Ratings, Audience Feedback, and Content Quality Analysis  
**Date:** 21 March 2026  
**Created by:** Soham S. Amburle  

---

## Overview

The **Viewer Ratings Analysis Dashboard** provides a comprehensive view of audience feedback and content quality across a global streaming platform.

Built using a synthetic dataset and a snowflake schema data model, this dashboard enables analysts to evaluate **viewer satisfaction, rating distribution, and content performance based on audience feedback**.

This dashboard answers key analytical questions:

* How are ratings distributed across the platform?
* What proportion of ratings are high vs low?
* Which genres receive the highest ratings?
* Which content titles are rated the highest?
* How does audience feedback vary across content types?

Through KPI cards, charts, and slicers, the dashboard delivers an **interactive and insight-driven analysis of viewer sentiment**.

---

## Business Storyline & Analytical Flow

### 1. Ratings Overview – KPI Cards

Seven KPI cards provide a high-level snapshot:

* **Avg Rating**
* **Total Ratings**
* **Rated Users**
* **Rated Titles**
* **High Rating % (4+)**
* **Low Rating % (≤2)**
* **Avg Ratings / User**

These KPIs help stakeholders quickly assess **overall satisfaction, engagement, and feedback distribution**.

---

### 2. Main Analytical Visuals

Five visuals provide deeper insights into ratings:

1. **RATING DISTRIBUTION** – Column Chart (Unit: Count)  
2. **AVG RATING BY GENRE** – Bar Chart (Unit: Rating Score)  
3. **TOP 10 CONTENT BY RATING** – Area Chart (Unit: Rating Score)  
4. **RATINGS BY CONTENT TYPE** – Donut Chart (Unit: Distribution %)  
5. **RATING DISTRIBUTION BY GENRE** – Stacked Bar Chart (Unit: Count)  

These visuals highlight **rating trends, genre performance, and audience preferences**.

---

### 3. Interactive Slicers

Eight slicers enable dynamic filtering:

* Content Type (`Dim_Content[ContentType]`)
* Genre (`Dim_Genre[GenreName]`)
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

* Understand audience sentiment through rating distribution  
* Identify highly rated and poorly rated content  
* Analyze genre-level performance based on ratings  
* Evaluate content quality across content types  
* Support data-driven content improvement and recommendation strategies  

---

## Tools & Data

* **Visualization Tool:** Power BI  
* **Dataset:** Synthetic global streaming dataset  
* **Record Count:** ~2,394 rows  
* **Data Model:** Snowflake Schema  
* **Purpose:** Viewer feedback and content quality analytics for BI portfolio  

---

> **Note:** This project is not affiliated with Netflix. All data is synthetic and created solely for educational and portfolio purposes.

---

**Dashboard and Documentation by SOHAM S. AMBURLE**  
**21 March 2026**

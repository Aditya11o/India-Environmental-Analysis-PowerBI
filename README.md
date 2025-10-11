# Environmental Reports: India Data Analysis Portfolio

This repository contains my complete data analytics portfolio focused on exploring critical environmental and demographic challenges across India using **Microsoft Power BI**. The project demonstrates proficiency in the full data workflow: collection, cleaning, modeling, and delivering interactive, actionable dashboards.

---

## Project Overview (4 Interactive Dashboards)

This analysis is broken down into four key areas, with each dashboard designed for specialized insights:

### 1. Air Quality & Pollution (AQI)

* **File:** `AQI_Pollution_Dashboard.pbix`
* **Focus:** Visualizing Air Quality Index (AQI) trends, comparison of primary pollutant concentrations (PM2.5, NO2, SO2), and identifying most-affected regions and cities.

![Air Quality Dashboard Preview](Dashboard_Previews/AQI_Pollution_Dashboard_Preview.png) 

### 2. Greenhouse Gas (GHG) Emissions

* **File:** `GHG_CO_Emissions_Analysis.pbix`
* **Focus:** Detailed analysis of Carbon Monoxide (CO) levels, max/min trends, and identifying potential correlation with industrial areas across various states.

![GHG Emissions Dashboard Preview](Dashboard_Previews/GHG_CO_Emissions_Analysis_Preview.png) 

### 3. Population and Demographics

* **File:** `India_Major_City_Population.pbix`
* **Focus:** Analysis of population distribution, growth rates, and density within India's largest metropolitan areas (cities with population > 1 million).

![Population Analysis Dashboard Preview](Dashboard_Previews/India_Major_City_Population_Preview.png) 

### 4. City Climate and Temperature

* **File:** `City_Temperature_Climate_Insights.pbix`
* **Focus:** Visualizing temperature, humidity, and weather conditions to identify seasonal patterns and anomalies in major Indian cities.

![Climate Insights Dashboard Preview](Dashboard_Previews/City_Temperature_Climate_Insights_Preview.png) 

---

## Key Analytical Insights

The analysis across these four dashboards revealed several critical findings, providing a strong basis for policy and strategic discussion:

### 1. Strong Correlation Between Population Density and Pollutants

* **Insight:** Cities with the highest population densities (e.g., Delhi, Kolkata, Mumbai) consistently record the highest average concentrations of major pollutants (PM2.5, PM10, and CO) across the nation.
* **Recommendation:** Policy interventions should prioritize **Sustainable Urban Mobility** by significantly investing in public transport infrastructure and enforcing stricter vehicular emission standards in these high-density metropolitan areas to mitigate air quality deterioration.

### 2. Seasonal Vulnerability in Northern Regions (Temperature Impact)

* **Insight:** The dataset shows that air quality (AQI) significantly worsens (records higher values) during months with lower average temperatures, particularly across major Northern cities (e.g., Lucknow, Jaipur). This seasonal trend is likely influenced by atmospheric inversions and increased burning activities.
* **Recommendation:** Implement **specific seasonal (winter) action plans** in these vulnerable regions, focusing on controlling emissions from domestic heating, biomass burning, and managing industrial output during the colder, high-risk periods.

### 3. Industrial and Localized Hotspots for CO and GHG Emissions

* **Insight:** States known for heavy industrial activity (e.g., Maharashtra, Gujarat) show consistently elevated levels of Greenhouse Gases (GHG) and Carbon Monoxide (CO). Furthermore, certain Tier-2 cities like Patna and Muzaffarpur stand out for high CO levels, pointing to specific, localized sources.
* **Recommendation:** Regulatory bodies should conduct **targeted audits** on key industrial clusters and introduce incentives for transitioning to cleaner fuel sources, coupled with Zonal Pollution Control policies to address distinct urban hotspots.

---

## Technology and Data Workflow

* **Primary Tool:** **Microsoft Power BI** (for data modeling, DAX, and visualization).
* **Data Sources:** Multiple **CSV** and **XLSX** files sourced from public domains.
* **Data Transformation:** **ETL process** performed using Power Query (M Language) for data cleaning, merging, and type casting.
* **Repository Structure:** Files are organized into dedicated folders for **Data**, **PowerBI_Dashboards**, and **Dashboard_Previews** for maximum readability.

---

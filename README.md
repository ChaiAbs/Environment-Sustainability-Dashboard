# 🌿 Environment Sustainability Dashboard 2024

> An interactive Power BI dashboard tracking key environmental sustainability metrics across emissions, energy, biodiversity, water, and waste.

**Course:** INFS5700 · Group Assignment · W18A · Group 1  
**Tool:** Microsoft Power BI (Cloud, Release 2023.02)

---

## 📋 Table of Contents

- [Overview](#overview)
- [Dashboard Sections](#dashboard-sections)
- [Key KPIs](#key-kpis)
- [Data Sources](#data-sources)
- [File Structure](#file-structure)
- [How to Open](#how-to-open)
- [Team](#team)

---

## Overview

This dashboard provides a comprehensive view of an organisation's environmental sustainability performance. It is structured into four interactive sections, navigated via on-screen buttons, and benchmarks current performance against defined **2025 sustainability targets**.

The report follows the **GHG Protocol** framework for emissions reporting (Scope 1, 2, and 3) and tracks additional ESG pillars including renewable energy, campus biodiversity, water consumption, and waste diversion.

---

## Dashboard Sections

### 🔥 1. Emissions + Electricity & PV


![Emissions Dashboard](https://github.com/ChaiAbs/Environment-Sustainability-Dashboard/blob/main/Screenshot%202026-04-06%20at%2011.40.14.png)

Tracks greenhouse gas emissions across all three GHG Protocol scopes.

| Visual | Description |
|--------|-------------|
| Line Chart | Scope 2 indirect emissions (electricity) over time |
| 100% Stacked Bar | Scope 1 direct emissions — livestock, natural gas, refrigerants |
| 100% Stacked Column | Scope 3 value chain emissions (Categories 1–15) |
| Clustered Column | Voluntary carbon surrenders by year |
| KPI Card | Energy intensity vs 2025 target |



Monitors solar photovoltaic capacity and energy intensity performance.

| Visual | Description |
|--------|-------------|
| Clustered Column | PV capacity installed per year |
| Line Chart | Energy intensity vs 2025 target (189 kWh/m² GFA) |
| KPI Cards | 2025 targets: PV capacity 5.71 MW, Energy intensity 189 |
---


### 🌳 2. Trees
A full campus tree inventory combining geospatial mapping with health and structural analysis.

![Trees Dashboard](https://github.com/ChaiAbs/Environment-Sustainability-Dashboard/blob/main/Screenshot%202026-04-06%20at%2011.41.03.png)

| Visual | Description |
|--------|-------------|
| Bubble Map | Tree locations — bubble size = canopy spread, colour = height |
| Donut Charts | Health status, structural assessment, life expectancy |
| Clustered Columns | Height, canopy spread, and age distributions |
| KPI Cards | Total tree count, number of unique species |

---

### 💧 3. Water & Waste
Tracks water consumption intensity and solid waste generation against sustainability targets.

![Water & Waste Dashboard](https://github.com/ChaiAbs/Environment-Sustainability-Dashboard/blob/main/Screenshot%202026-04-06%20at%2011.40.34.png)

| Visual | Description |
|--------|-------------|
| Line Chart | Water intensity vs 2025 target (0.9 kL/m² GFA) |
| 100% Stacked Column | Bore water vs potable water split by year |
| Column Chart | Waste generation by category (2018–2022) |
| Clustered Column | Recycling and landfill diversion rates (2022) |
| Donut Chart | Waste treatment methods breakdown |

---

## Key KPIs

| Metric | Current | 2025 Target |
|--------|---------|-------------|
| Energy Intensity | — | 189 kWh/m² GFA |
| PV Capacity | 5.71 MW | 1.5 MW ✅ |
| Water Intensity | 3.87 kL/m² | 0.9 kL/m² |
| GHG Emissions | Tracked | Year-on-year reduction |

> ⚠️ Water intensity (3.87 kL/m²) is currently well above the 2025 target of 0.9 kL/m² and represents the most significant area for improvement.

---

## Data Sources

The following datasets are embedded in the Power BI model:

| Table | Contents |
|-------|----------|
| `Emissions cleaned` | Scope 1, 2, 3 emissions by year |
| `Table 1 (Elec data)` | Electricity consumption and PV capacity |
| `Table 1 (Water data)` | Potable and bore water consumption |
| `tree_data_cleaned` | Campus tree inventory (species, GPS, health, age, structure) |
| `waste_data_corrected` | Waste generation by category (2018–2022) |
| `waste_treemap_cleaned` | Recycling diversion rates and treatment methods |

---


## How to Open

1. Download the `.pbix` file from the `dashboard/` folder
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free download)
3. Use the navigation buttons at the top of the report to switch between sections

> **Note:** The data model uses XPress9 (VertiPaq) compression. No additional data source connections are required — all data is embedded in the file.

---

## Team

**INFS5700 · W18A · Group 1**

> Built with 💚 using Microsoft Power BI

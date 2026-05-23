# 📊 Displaced Families Demographic & Socioeconomic Analytics Dashboard

[![Power BI](https://img.shields.io/badge/Data_Visualization-Power_BI-yellow?style=flat&logo=powerbi)](https://powerbi.microsoft.com/)
[![Data Pipeline](https://img.shields.io/badge/ETL-Power_Query-teal?style=flat)](https://powerbi.microsoft.com/)
[![Status](https://img.shields.io/badge/Project_Status-Completed-success?style=flat)]()

An interactive, high-impact Power BI dashboard built to analyze demographic distributions, operational reach, financial metrics, and severe housing vulnerabilities for **1,701 displaced families** across four nations: **Syria, Yemen, Iraq, and Libya**. 

This intelligence tool is structured to empower NGOs, UN agencies, and humanitarian groups to pinpoint regional crisis thresholds, track vulnerable demographics, and allocate emergency relief efficiently.

---

## 🚀 Dashboard Overview
<img width="1379" height="792" alt="Screenshot 2026-05-23 234216" src="https://github.com/user-attachments/assets/d28b7f05-eb23-49d0-9042-33626548cb04" />

---

## 🚀 Key System Features

* **Comprehensive Aggregations:** Instantly processes high-level key metrics such as family-to-member ratios, regional metrics, and income breakdowns.
* **Vulnerability Frameworks:** Explicitly maps critical shelter needs by isolating numbers of families currently forced to live in temporary tents.
* **Demographic Proportionality:** Offers precise insights into gender breakdowns and counts of specialized minor cohorts (Females Under 18) to ensure protection standards are systematically met.
* **Cohesive Design System:** Implements a professional, desaturated dark teal and soft aqua corporate palette designed to preserve data hierarchy and enhance readability in professional stakeholder briefings.

---

## 📊 Dashboard Architecture & Data Snapshot

The analytical layout is structured into two main segments: static high-level metric cards on the left for foundational understanding, and regional trend charts on the right for deep-dive discovery.

### 1. High-Level Performance Matrix (KPI Cards)
* **Total Registered Families:** `1,701`
* **Total Individuals Covered:** `11,905`
* **Vulnerable Minor Demographics (Female < 18):** `2,695`
* **Cumulative Regional Income Volume:** `58,385`
* **Calculated Average Family Income:** `85.61`
* **Specialized Cohort Metrics (Members of Mothers...):** `3,999`

### 2. Analytical Visuals & Regional Splits
* **Families by Country (Column Chart):** Highlights regional density concentrations, identifying *Syria* (`647`) and *Yemen* (`606`) as the highest density focal points, followed evenly by *Iraq* (`224`) and *Lybia* (`224`).
* **Operational Reach (Funnel Chart):** Tracks the number of unique operational cities audited per nation (*Yemen*: `6`, *Syria*: `5`, *Iraq*: `4`, *Lybia*: `4`).
* **Global Gender Ratio (Donut Chart):** Visualizes the broader community gender distribution, highlighting a significant margin tilt at **55% Female** versus **45% Male**.
* **Shelter Disparity Index (Horizontal Bar Chart):** Measures extreme vulnerability, charting families stranded in temporary tents per country (*Syria*: `138`, *Yemen*: `120`, *Iraq*: `45`, *Lybia*: `41`).

---

## 🛠️ Data Engineering & Visual Stack

* **Reporting & Visual Layer:** Power BI Desktop
* **Data Cleansing / ETL Engine:** Power Query (Used for handling missing values, standardizing regional text parameters, grouping localized data metrics, and configuring explicit structural hierarchy schemas).

---

## 💡 Strategic Takeaways for Stakeholders

1. **Immediate Shelter Crisis:** Combined, Syria and Yemen represent over **84.3% of the entire tent-bound population** inside this matrix (258 out of 344 total tented families). Strategic resource allocations for winterization or permanent housing initiatives should be heavily prioritized here.
2. **Gender-Responsive Programming:** Because females comprise **55%** of the general census population alongside **2,695** minor girls, specialized healthcare, localized protection programs, and specific hygiene supplies must scale proportionally.
3. **ETL Quality Note:** The label string `"Lybia"` on the visual interface reflects historical spelling constraints directly imported from the raw database layers. A planned Power Query pipeline optimization pass will incorporate a text replacement component to match the universal standard (`"Libya"`).

---

## 📁 Repository Structure

```text
├── Data/                             # Mock source data files or schemas
├── Documentation/                    # Functional specification metrics
├── Visuals/                          # Raw high-resolution dashboard screenshots
├── Displaced_Families_Report.pbix    # Main Power BI Workbook package
└── README.md                         # Main documentation file

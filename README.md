# Life Expectancy Analysis Dashboard (Power BI)

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/Language-DAX-blue)
![Dataset](https://img.shields.io/badge/Data-WHO%20Life%20Expectancy-green)

An interactive Power BI dashboard that transforms WHO health data into actionable insights on why some countries live longer than others.

---

## Table of Contents

- [Business Problem](#business-problem)
- [Solution](#solution)
  - [Key Performance Indicators](#1-key-performance-indicators-kpis)
  - [Correlation and Trend Analysis](#2-correlation-and-trend-analysis)
  - [Data Visualization](#3-data-visualization)
- [KPI Cards and DAX Measures](#kpi-cards-and-dax-measures)
- [Dashboard Preview](#dashboard-preview)
- [Summary](#summary)
- [Tools Used](#tools-used)

---

## Business Problem

### Why do some countries live longer than others?

Governments, public health organizations, and NGOs need to understand the factors associated with low life expectancy, particularly in developing countries. Despite investments in healthcare and vaccination programs, identifying the key factors influencing health outcomes remains a challenge.

**Main areas of concern:**

- Understanding healthcare expenditure and its relationship with health outcomes
- Analyzing the impact of malnutrition and infant mortality
- Evaluating vaccination coverage
- Examining the relationship between GDP and life expectancy
- Understanding how education and lifestyle factors relate to longevity

Stakeholders need a data-driven solution to identify patterns, monitor trends, and support informed decision-making.

---

## Solution

The **Life Expectancy Dashboard** transforms WHO health data into meaningful insights through the following features.

### 1. Key Performance Indicators (KPIs)

- Average Life Expectancy
- Average Infant Deaths
- Average Adult Mortality
- Total Population
- Average Schooling Years
- Vaccination Index
- Average GDP
- GDP per Capita
- Total Health Expenditure
- Average HIV Indicator

These indicators provide an overview of health, economic, and demographic conditions.

### 2. Correlation and Trend Analysis

- Analyze the relationship between GDP and life expectancy
- Track life expectancy trends across countries and years
- Compare developed and developing countries
- Examine relationships between HIV/AIDS, malnutrition, and life expectancy
- Analyze the relationship between vaccination coverage, education, and health outcomes

This analysis helps identify patterns and areas that may require further investigation.

### 3. Data Visualization

The dashboard uses interactive visualizations to make the data easier to understand:

| Visual | Purpose |
|---|---|
| Bar charts | Country comparisons and rankings |
| Maps | Geographic differences in life expectancy |
| Scatter plots | Analyzing relationships between indicators |
| Heatmaps | Comparing changes across countries and years |
| Smart Narratives | Automatically generated summaries of data insights |

---

## KPI Cards and DAX Measures

| KPI | DAX Measure |
|---|---|
| Average Life Expectancy | `AvgLifeExpectancy` |
| Average Infant Deaths | `AvgInfantDeaths` |
| Average Adult Mortality | `AvgAdultMortality` |
| Total Population | `TotalPopulation` |
| Average Schooling Years | `AvgSchoolingYears` |
| Vaccination Index | `VaccinationIndex` |
| Average GDP | `AvgGDP` |
| GDP per Capita | `GDPPerCapita` |
| Health Expenditure | `HealthExpenditureAbsolute` |
| Average HIV Indicator | `AvgHIVRate` |

---

## Dashboard Preview

### Dashboard 1 – Overview

![Life Expectancy Dashboard - Overview](https://github.com/user-attachments/assets/96b78784-e98e-4191-b0b9-7507681428d1)

### Dashboard 2 – Analysis

![Life Expectancy Dashboard - Analysis](https://github.com/user-attachments/assets/1443c150-24ce-4f27-b018-ad5a06babe66)

### Dashboard 3 – Insights

![Life Expectancy Dashboard - Insights](https://github.com/user-attachments/assets/45654407-e0fe-4ca5-9f97-2478c96db32e)

---

## Summary

The Life Expectancy Analysis Dashboard transforms health data into an interactive reporting solution using Microsoft Power BI. It enables users to compare countries, monitor trends, and explore relationships between life expectancy, healthcare expenditure, vaccination, education, economic development, and other health indicators.

The project supports data-driven exploration of global health inequalities and provides insights that can help inform public health research, planning, and decision-making.

---

## Tools Used

- **Microsoft Power BI**
- **DAX**
- **WHO Life Expectancy Dataset**

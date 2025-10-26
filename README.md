# 📊 U.S. City-Wise Energy Consumption Dashboard (2023–2024) | Power BI Project

An interactive Power BI dashboard to analyze and compare energy consumption patterns across Chicago, New York, and Atlanta using historical data from January 2023 to December 2024.


# Energy Dashboard Analysis

## Table of Contents
- [Project Title](#project-title)
- [Brief One-Line Summary](#brief-one-line-summary)
- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Tools and Technologies](#tools-and-technologies)
- [Methods](#methods)
- [Key Insights](#key-insights)
- [DashboardModelOutput](#dashboardmodeloutput)
- [How to Run this Project](#how-to-run-this-project)
- [Results & Conclusion](#results--conclusion)

## Project Title
Energy Consumption Dashboard for Chicago, New York, and Atlanta (2023–2024)

## Brief One-Line Summary
An interactive Power BI dashboard analyzing and visualizing monthly energy consumption trends across three major US cities.

## Overview
This project visualizes energy usage data collected from Chicago, New York, and Atlanta between January 2023 and December 2024. Using Power BI, it uncovers trends, peak usage patterns, and comparative insights between the cities to support data-driven decisions.

## Problem Statement
Utility providers and city energy departments often deal with large volumes of usage data without actionable insights. This project aims to bridge that gap by visualizing energy consumption patterns clearly and interactively.

## Dataset
The datasets used are monthly CSV files titled `April_2023.csv`, `April_2024.csv`, and others from the same series (January 2023 to December 2024). Each contains location-wise energy usage, timestamps, and other metadata.

## Tools and Technologies
- Power BI (Dashboard Development)
- Microsoft Excel (Data Cleaning)
- CSV Files (Data Source Format)
- DAX (Data Analysis Expressions for KPIs and Measures)

## Methods
- Data extraction from multiple CSVs
- Data transformation and cleaning in Power BI Query Editor
- Visual creation of KPIs, time-series trends, bar/line charts, and filters
- Slicers added for dynamic filtering by location and date

## Key Insights
- New York consistently showed higher average monthly consumption than Chicago and Atlanta.
- Seasonal consumption patterns observed: Peaks in summer and winter months.
- Significant reduction in usage in Atlanta during Q2 of 2024.
- Certain months had data irregularities needing attention (e.g., missing values).

## DashboardModelOutput
The Power BI `.pbix` file includes:
- **Monthly Trend Lines** for each location
- **Location-wise Comparison** bar charts
- **KPI Cards** (e.g., Total Consumption, Monthly Change)
- **Dynamic Filters** for Location and Time
- **Data Model** integrating multi-year datasets

## How to Run this Project
1. Install Power BI Desktop.
2. Open the file `ENERGY DASHBOARD.pbix`.
3. Make sure all CSV files (2023–2024) are in the same directory or reassign the source paths in Power BI.
4. Refresh data to load the most recent updates.
5. Use the slicers and visuals to explore energy trends.

## Results & Conclusion
The dashboard provides stakeholders with actionable insights into energy usage trends across three major cities. It empowers urban energy management, supports demand forecasting, and promotes sustainable energy planning.

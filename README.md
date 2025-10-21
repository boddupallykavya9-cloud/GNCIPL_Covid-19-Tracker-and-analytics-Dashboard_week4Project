# COVID-19 Global Tracker & Dashboard

A comprehensive Power BI project for visualizing, analyzing, and tracking worldwide COVID-19 trends, impacts, and recoveries using open-source datasets.

## Project Overview

This dashboard tracks the spread, severity, and recovery trends of COVID-19 across countries using real-world datasets. It summarizes daily new cases, cumulative totals, deaths, recovery/mortality rates, and provides interactive global visualizations for deep analysis.

## Features

*   **ETL Workflow:**
    *   Extracted data from sources such as Johns Hopkins University, WHO, and Kaggle.
    *   Transformed using Power Query: standardized country names, cleaned missing/null values, formatted dates.
    *   Loaded as a clean table into Power BI for analytics.
*   **Key Metrics & DAX Measures:**
    *   Daily New Cases
    *   Cumulative Cases (Running Total)
    *   Recovery Rate
    *   Mortality Rate
    *   Visualized via KPI Cards, trend charts, maps, and tables.
*   **Visualizations:**
    *   Interactive world heatmap (geographical spread)
    *   Time-series line charts (case trends by country)
    *   KPI cards (recovery, active, death totals, rates)
    *   Data tables with daily breakdowns
    *   Slicer/filters for dynamic analysis
*   **Advanced Reporting:**
    *   Data challenges and cleaning techniques are noted.
    *   Ready for further extensions (e.g., vaccine data integration, forecasting).

## How To Run

*   Clone/Download this repository
*   Open `covid_project.pbix` in Power BI Desktop
*   **For raw data and transformation steps:** Open Power Query via "Transform Data" menu for preprocessing details.
*   Explore visuals with interactive filters and see measures update live.

## Data Sources

*   Johns Hopkins University COVID-19 GitHub
*   World Health Organization
*   Kaggle COVID-19 datasets

## Methodology

*   **ETL:** Data extraction, cleaning, and standardization in Power Query.
*   **DAX Measures:** Multiple calculated fields for core metrics.
*   **Visualization:** Use of map, line, table, and card visuals for best insight.

## Challenges

*   Inconsistent country naming resolved in Power Query.
*   Missing or incomplete data handled with DAX formulas.
*   Standardized date formats for global comparability.

## Attribution & License

All analytics and code are based on publicly available COVID-19 data. Datasets retained under respective providers’ licenses.

## Extensions & Ideas

*   Add vaccination data or predictive modeling for future trends.
*   Drill down to regional/state-level analysis.
*   Integrate additional health/demographic overlays.

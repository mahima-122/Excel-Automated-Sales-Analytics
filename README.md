# Automated Sales Consolidation & Financial Dashboard

## Project Overview
This project demonstrates the transition from manual spreadsheet management to automated data engineering using Excel. By leveraging **Power Query**, I engineered an ETL (Extract, Transform, Load) pipeline that consolidates fragmented, multi-year sales data into a single, dynamic master dashboard.

## Tech Stack
- **Data Engineering:** Power Query (Excel ETL)
- **Data Modeling:** Pivot Tables & Advanced Slicers
- **Business Logic:** Data Visualization & Trend Analysis

## The Automated Pipeline
The core value of this project is the automation of data ingestion:
1.  **Data Consolidation:** Instead of manual copy-pasting, I implemented a **"Get Data from Folder"** workflow.
2.  **ETL Process:** 
    - **Extract:** Automatically pulls multiple annual Excel files from a directory.
    - **Transform:** Standardized schema, handled data types (Date/Currency), and engineered a custom `Order_Year` column for time-series analysis.
    - **Load:** Automatically refreshed the Master Table to include new data instantly upon folder updates.

## Dashboard Insights
The dashboard serves as a decision-support tool for retail management:
- **Trend Analysis:** Visualized annual revenue and profit trajectories, highlighting growth patterns from 2014–2018.
- **Comparative Performance:** Enabled "side-by-side" comparison of product categories using dynamic Slicers.
- **Operational Intelligence:** Created interactive Pivot Charts that allow stakeholders to toggle between years, regions, and categories without needing to manipulate raw data.

## Key Learning Outcomes
- **Automation:** Reduced manual reporting time by ~90% by building a "Refresh-to-Update" dashboard.
- **Data Integrity:** Ensured consistent reporting standards across multi-year datasets by cleaning and structuring data at the source.
- **Storytelling:** Developed intuitive visualizations that translate complex multi-year trends into clear executive summaries.

## 📂 Repository Contents
- `Superstore_Automated_Dashboard.xlsx`: The master Excel file containing the automated pipeline and Pivot-based dashboard.
- `Sales_Reports/`: Sample directory structure showcasing how the automation integrates new data sources.
- `Dashboard_Screenshots.png`: Visual overview of the interactive dashboard and slicer functionality.

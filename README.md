# E-Commerce Executive Category, Sales & Product Analytics Dashboard

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Category Analytics](https://img.shields.io/badge/Category_Analytics-Executive_Reporting-blue?style=for-the-badge)

An interactive, executive-ready category, sales, and product performance dashboard built in **Microsoft Excel**. This project transforms raw e-commerce transaction data into dynamic corporate intelligence, enabling stakeholders to evaluate category performance, revenue trajectories, top-performing inventory, and global market distributions in real time.

---

## Project Overview

This category analytics solution was engineered to support high-level corporate decision-making and category growth strategy. By unifying category revenue trends, SKU rankings, and regional category performance into a single reporting layout, the dashboard provides both macro-level category insights and granular drill-down capabilities.

### Key Objectives:
* **Category & Product Performance Tracking:** Evaluate category revenue contribution and identify top-performing SKUs to optimize category management, stock allocation, and promotional focus.
* **Temporal Category Trend Analysis:** Evaluate month-over-month category revenue alongside volume sold to pinpoint seasonal demand shifts across product categories.
* **Geographic Market & Category Distribution:** Analyze category revenue share across international markets to uncover category expansion opportunities.

---

## Dashboard Architecture & Category Analytics Features

The dashboard consists of three core visual modules controlled by dynamic cross-filtering slicers:

| Visual Module | Chart Type | Category Analytics Insights Delivered |
| :--- | :--- | :--- |
| **Top Best-Selling Products** | Horizontal Bar Chart | Ranks top products by revenue contribution to guide category management and inventory allocation. |
| **Monthly Revenue vs. Volume** | Dual-Axis Combo Chart | Tracks category revenue growth trends alongside total units sold from 2010 to 2011. |
| **Country Revenue Breakdown** | Distribution Pie Chart | Visualizes global category sales share across key international markets and territories. |

### Dynamic Category Controls
* **MonthYear Slicer:** Filter all category metrics by specific monthly reporting periods.
* **Country Slicer:** Isolate category performance by specific geographic regions.
* **Report Connections:** Explicitly linked across all underlying PivotTables to ensure real-time cross-filtering of category analytics across all visual elements simultaneously.

---

## Data Engineering & Category Cleaning Workflow

Prior to building the visual interface, raw transactional records (`E_Commerce data`) were processed using the following category data hygiene steps:

1. **Date & Category Artifact Removal:** Sanitized `InvoiceDate` and category-related records to eliminate blank/null entries that cause `1900-01` date formatting errors in PivotTables.
2. **Category Revenue Standardisation:** Formatted revenue fields (`TotalRevenue`) to standard financial currency formats for accurate category reporting.
3. **Data & Category Integrity Checks:** Verified unit prices, quantity fields, and product categories to prevent skewed category summary metrics.

---

## Design & Layout Standards

Built following modern category analytics executive reporting design principles:
* **Clean Canvas:** Spreadsheet gridlines removed for a modern application feel.
* **Category Visual Hierarchy:** Arranged KPI summaries, category charts, and metrics logically to facilitate fast visual scanning.
* **Typography & Palette:** Clean layout with standardized chart titles and distinct visual color groupings.
* git lfs install
* git lfs track "*.xlsx"
* git add .gitattributes
* git add your_large_file.xlsx
git commit -m "Add large file via Git LFS"
git push origin main
git lfs install
git lfs track "*.xlsx"
git add .gitattributes
git add your_large_file.xlsx
git commit -m "Track file with Git LFS"
git push origin main
---

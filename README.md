#  E-Commerce Executive Sales & Product Analytics Dashboard

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-Executive_Reporting-blue?style=for-the-badge)


An interactive, executive-ready sales and product performance dashboard built in **Microsoft Excel**. This project transforms raw e-commerce transaction data into dynamic corporate intelligence, enabling stakeholders to evaluate revenue trajectories, top-performing inventory, and global market distributions in real time.

---

## Project Overview

This analytics solution was engineered to support high-level corporate decision-making and operational strategy. By unifying revenue trends, SKU rankings, and regional performance into a single reporting layout, the dashboard provides both macro-level business insights and granular drill-down capabilities.

### Key Objectives:
* **Product Performance Tracking:** Identify top revenue-generating SKUs to optimize inventory allocation and marketing focus.
* **Temporal Trend Analysis:** Evaluate month-over-month sales revenue alongside volume sold to pinpoint seasonality and demand shifts.
* **Geographic Market Distribution:** Analyze global revenue share across international markets to uncover growth opportunities.

---

## Dashboard Architecture & Features

The dashboard consists of three core analytical visual modules controlled by dynamic cross-filtering slicers:

| Visual Module | Chart Type | Key Insights Delivered |
| :--- | :--- | :--- |
| **Top Best-Selling Products** | Horizontal Bar Chart | Ranks top 10 products by total revenue contribution to guide inventory management. |
| **Monthly Revenue vs. Volume** | Dual-Axis Combo Chart | Tracks revenue growth trends alongside total units sold from 2010 to 2011. |
| **Country Revenue Breakdown** | Distribution Pie Chart | Visualizes global sales share across key international markets and territories. |

### Interactive Controls
* **MonthYear Slicer:** Filter all dashboard elements by specific monthly reporting periods.
* **Country Slicer:** Isolate sales metrics by specific geographic regions.
* **Report Connections:** Explicitly linked across all underlying PivotTables to ensure real-time cross-filtering across all visual elements simultaneously.

---

## Data Engineering & Cleaning Workflow

Prior to building the visual interface, raw transactional records (`E_Commerce data`) were processed using the following data hygiene steps:

1. **Date Artifact Removal:** Sanitized `InvoiceDate` records to eliminate blank/null entries that cause `1900-01` date formatting errors in PivotTables.
2. **Currency Standardisation:** Formatted revenue fields (`TotalRevenue`) to standard financial currency formats.
3. **Data Integrity Checks:** Verified unit prices and quantity fields to prevent skewed summary metrics.

---

## Design & Layout Standards

Built following modern executive reporting design principles:
* **Clean Canvas:** Spreadsheet gridlines removed for a modern application feel.
* **Visual Hierarchy:** Arranged KPI summaries and charts logically to facilitate fast visual scanning.
* **Typography & Palette:** Clean layout with standardized chart titles and distinct visual color groupings.

---

## 📂 Repository Structure

```text
├── data/
│   └── E_Commerce_data.csv        # Cleaned dataset used for analysis
├── dashboard# Category-Analytics

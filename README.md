# Retail Sales Executive Growth Dashboard

An end-to-end Excel business intelligence project covering data cleaning, transformation, DAX measures, and an interactive executive dashboard built on a simulated retail sales dataset.

---

## Dashboard Preview

![Executive Growth Overview Dashboard]()

---

## Project Overview

This project simulates the role of a data analyst tasked with building an executive-level dashboard for a retail business. Starting from a raw CSV file with data quality issues, the full pipeline was completed inside Microsoft Excel — from ingestion and cleaning in Power Query, through data modelling and DAX measure creation, to a polished dark-themed interactive dashboard.

---

## Dataset

| Detail | Value |
|--------|-------|
| Source | Simulated retail environment (educational dataset) |
| Records | 1,825 rows |
| Columns | Date, Category, Sales, Quantity, Profit, Region |
| Categories | Electronics, Clothing, Home Goods, Books, Sports |
| Regions | North, East, South, West |
| Period | 2023 |

**Data Quality Issues Identified:**
- Missing and inconsistent values in the Category column (NaN entries)
- Anomalous category labels requiring standardization

---

## Tools Used

- **Microsoft Excel** — Full project tool
- **Power Query** — Data ingestion, cleaning, and transformation
- **DAX (Data Analysis Expressions)** — Measure creation for KPIs
- **Pivot Tables** — Aggregation and breakdowns
- **Excel Charts** — Line charts and horizontal bar charts
- **Excel Slicers & Timeline** — Interactive filtering

---

## What Was Built

### 1. Data Cleaning (Power Query)
- Loaded raw CSV into Excel via Power Query
- Handled null and NaN values in the Category column
- Fixed inconsistent category labels and standardized formatting
- Ensured correct data types across all columns
- Removed anomalous entries and prepared a clean analysis-ready table

### 2. Data Modelling
- Built a dedicated Date Table for time intelligence support
- Established one-to-many relationships between the Date Table and the sales data
- Structured the model to support accurate time-based calculations

### 3. DAX Measures
The following measures were created to power the KPI cards:

| Measure | Description |
|---------|-------------|
| Total Revenue | Sum of all sales revenue |
| Previous Month Revenue | Revenue from the prior month |
| MoM Revenue Growth | Month-over-month revenue change (%) |
| Total Quantity | Total units sold |
| Previous Month Quantity | Units sold in the prior month |
| MoM Quantity Growth | Month-over-month quantity change (%) |
| Total Profit | Sum of all net profit |
| Previous Month Profit | Profit from the prior month |
| MoM Profit Growth | Month-over-month profit change (%) |
| Profit Margin | Total Profit as a percentage of Total Revenue |

### 4. Analysis Sheet
Pivot-based breakdowns covering:
- Revenue, Quantity, and Profit by Week
- Revenue, Quantity, and Profit by Category
- Revenue by Region

### 5. Executive Dashboard
A dark-themed, card-based interactive dashboard titled **Executive Growth Overview** with the subtitle *Real-time analysis of revenue, volume and profitability trend*.

**KPI Cards:**
- Revenue: $1.79M | PM: $1.63M | MoM: ▲9.8%
- Quantity: 18,298 | PM: 16,722 | MoM: ▲9.4%
- Profit: $453.87K | PM: $415.16K | MoM: ▲9.3%

**Visuals:**
- Revenue Contribution by Category (horizontal bar chart)
- Unit Distribution by Segment (horizontal bar chart)
- Net Profit by Sector (horizontal bar chart)
- Weekly Revenue Fluctuation (line chart)
- Order Volume Cycle (line chart)
- Margin Stability Tracking (line chart)

**Interactive Features:**
- Date timeline slicer (monthly granularity)
- Region slicer (East, North, South, West)
- Sidebar navigation (Dashboard, Analysis, Contact)

---

## Key Findings

- Total revenue for the period reached **$1.79M** with a healthy month-over-month growth of **9.8%**
- **Books** led all categories in revenue at $371K, closely followed by Electronics ($364K), Clothing ($351K), and Home Goods ($347K)
- **Home Goods** had the highest unit volume at 3,800 units while Electronics had the lowest at 3,600
- **Profit margins were consistent across all categories** — Books, Sports, Electronics, and Clothing each generated approximately $90–92K in net profit
- Weekly trends show a **strong mid-period peak (Wk2–Wk4)** followed by a sharp decline in Wk6, suggesting end-of-period seasonality or data coverage cutoff

---

## Project Structure

```
retail-sales-dashboard/
├── retail_sales.csv              # Raw dataset
├── Retail_Sales_Dashboard.xlsx   # Excel workbook (Power Query, model, DAX, dashboard)
└── README.md
```

---

## Skills Demonstrated

- Data cleaning and transformation with Power Query
- Date table creation and data modelling in Excel
- DAX measure writing for time intelligence KPIs
- Pivot table aggregations and analysis
- Executive dashboard design with dark UI theme
- Interactive filtering with slicers and timeline

---

## Author

**Lucky Ogolo** — Data Analyst

- Portfolio: [luckyogolo.my.canva.site](https://luckyogolo.my.canva.site)
- GitHub: [github.com/Lucky-ogolo](https://github.com/Lucky-ogolo)
- LinkedIn: [linkedin.com/in/lucky-ogolo](https://linkedin.com/in/lucky-ogolo)

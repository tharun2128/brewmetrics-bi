# BrewMetrics BI

## Project Overview

BrewMetrics Coffee Co. operates Flagship stores, Kiosks and Drive-Thrus across four cities.

This Power BI project analyzes sales performance using the provided BrewMetrics sales dataset.

## Dataset

The project uses:

`brewmetrics_sales.csv`

The dataset contains transaction-level sales information including:

- Date
- City
- Store format
- Category
- Item
- Quantity
- Unit price
- Sales amount

## Data Model

The Power BI model uses a star schema.

### Fact Table

**Fact_Sales**

Contains transaction-level sales data.

### Dimension Tables

**Dim_Date**  
Contains date, year and month information.

**Dim_City**  
Contains city information.

**Dim_Product**  
Contains product and category information.

**Dim_Store**  
Contains store format information.

## DAX Measures

- Total Sales
- Month-over-Month Sales Growth
- Running Total Sales
- Item Sales Rank
- Average Sale Value

## Dashboard

The dashboard includes:

- Sales by city
- Cold Brew monthly sales
- Product sales
- KPI cards
- City slicer
- City → Store Format drill-down

## Key Insights

1. Bengaluru is the strongest-performing city in the dataset.

2. Cold Brew shows a stronger sales pattern during April and May.

3. The dashboard allows users to interactively compare city and store-format performance.

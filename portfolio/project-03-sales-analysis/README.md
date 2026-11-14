# Project 3 — Sales Analysis & Formula Sheet

**Portfolio category:** Excel / Sales Reporting / Beginner Data Analysis  
**Project type:** Independent practice sample · illustrative data

## Objective
Turn a small sales log into a concise report showing revenue, units sold, average transaction value and product contribution.

## Included
- `sales_data.csv` — 11 illustrative transactions with a row-level sales formula.
- KPI ideas: total sales, total units, average sale, highest sale and lowest sale.
- Suggested visuals: sales by product, product share of total revenue and sales over time.

## Spreadsheet formulas
Assuming the CSV is opened in Excel:
- **Total Sales:** `=SUM(E2:E12)`
- **Total Units Sold:** `=SUM(C2:C12)`
- **Average Sale:** `=AVERAGE(E2:E12)`
- **Highest Sale:** `=MAX(E2:E12)`
- **Lowest Sale:** `=MIN(E2:E12)`
- **Product Revenue (e.g. Keyboard):** `=SUMIF(B2:B12,"Keyboard",E2:E12)`
- **Product Share:** `=ProductRevenue/TotalSales`

## Data quality note
The reference image includes an example dashboard with some totals and chart labels that do not fully reconcile with the visible transaction rows. This sample calculates each row from units × unit price and derives all KPIs from the underlying data, rather than copying the mockup's headline totals. The figures may therefore differ from the reference image.

## Skills demonstrated
Excel formulas · SUMPRODUCT concept · SUMIF · AVERAGE · MAX/MIN · sales reporting · product mix analysis · chart planning

> This is a practice project, not paid client work or a live sales report.

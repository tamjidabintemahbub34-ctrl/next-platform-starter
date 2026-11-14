# Project 3 — Sales Analysis & Formula Sheet

**Portfolio category:** Excel / Sales Reporting / Beginner Data Analysis  
**Project type:** Independent practice sample · illustrative data

## Sample screenshot

![Project 3 — Sales Analysis & Formula Sheet](https://static.wixstatic.com/media/e31d82_1c151b4ef43e4139b806506934249fc5~mv2.png)

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
The screenshot is shown as supplied for portfolio presentation. Its figures and formulas have not been independently audited. Refer to the included CSV and calculate totals from the underlying rows before using this as a live business report.

## Skills demonstrated
Excel formulas · SUMPRODUCT concept · SUMIF · AVERAGE · MAX/MIN · sales reporting · product mix analysis · chart planning

> This is a practice project, not paid client work or a live sales report.

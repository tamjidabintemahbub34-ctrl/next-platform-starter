# Project 2 — Inventory Management Sheet

**Portfolio category:** Excel / Spreadsheet Support / E-commerce Operations  
**Project type:** Independent practice sample · illustrative data

## Objective
Create a clear inventory tracker that helps a small business review quantities, stock value, product categories and replenishment priorities.

## Included
- `inventory_data.csv` — 11 illustrative product records with calculated stock-value formulas.
- KPI ideas: total SKUs, total stock units, total inventory value, low-stock items and out-of-stock items.
- Suggested visuals: stock value by category, stock value trend (when dated movement data is available), and stock-status overview.

## Spreadsheet formulas
Assuming the CSV is opened in Excel:
- **Stock Value:** `=D2*E2` (copy down)
- **Total Stock Units:** `=SUM(D2:D12)`
- **Total Stock Value:** `=SUM(F2:F12)`
- **Low Stock Count:** `=COUNTIF(G2:G12,"Low Stock")`
- **Out of Stock Count:** `=COUNTIF(G2:G12,"Out of Stock")`

## Data quality note
The supplied visual reference contains illustrative values that do not all reconcile mathematically. This sample uses the visible product names and quantities, but corrects the external-drive quantity to 10 to match the reference's displayed £599.90 value. The dashboard should calculate totals from the underlying rows rather than copy a pre-filled total from a mockup. Set low-stock thresholds to match the store's own reorder policy.

## Skills demonstrated
Excel formulas · inventory tracking · data validation · conditional formatting · KPI design · category analysis · dashboard planning

> This is a practice project, not paid client work or a live inventory system.

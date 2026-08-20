# Lab 8: Create Core DAX Measures

**Level:** Advanced  
**Alignment:** LO6 · A6  
**Estimated time:** 60 minutes

## Scenario and goal

Use the supplied Excel evidence workbook and Power BI starter to produce: **Validated measures for Sales, Cost, Profit, Margin and share of total**.

## Files in this folder

- `Sales_Model.xlsx` - intake, control and audit-evidence workbook
- `starter.pbix` - clean Power BI starter file from the approved Microsoft learning assets already held in the course Drive
- `README.md` - editable lab guide
- `README.pdf` - printable lab guide

## Before you start

1. Use Power BI Desktop on Windows and work on a copy of `starter.pbix`.
2. Keep this folder structure intact so relative source paths are easier to repair.
3. Do not upload confidential or personal data to the training workspace.
4. Read the workbook Control and Evidence sheets before building.

## Step-by-step

1. Open `starter.pbix`, save a working copy, and import `Sales_Model.xlsx`.
2. Create a display folder named `Core Measures` and keep all new measures in a dedicated Measures table.
3. Create `Total Sales = SUM(FactSales[Sales])`.
4. Create `Total Cost = SUM(FactSales[Cost])` and `Profit = [Total Sales] - [Total Cost]`.
5. Create `Profit Margin = DIVIDE([Profit], [Total Sales])` and format it as a percentage with one decimal place.
6. Create `Order Quantity = SUM(FactSales[Quantity])`.
7. Create `Sales % All Region = DIVIDE([Total Sales], CALCULATE([Total Sales], REMOVEFILTERS(DimRegion)))`.
8. Use variables to create an `Average Order Value` measure from sales and distinct order count.
9. Build a matrix by Region and Category and add the measures in a deliberate order.
10. Test each measure with and without slicers to confirm it responds to filter context.
11. Reconcile Total Sales, Profit and Margin to the workbook Control sheet.
12. Document one filter-context test and one division-by-zero test in Evidence.

## Evidence to retain

- Saved PBIX working file with your name in the filename
- Screenshot of the relevant query, model, report or Service page
- Completed Excel Evidence sheet
- One finding, the supporting visual/measure, one limitation and one recommended action

## Acceptance criteria

- Measures reconcile to workbook controls and respond correctly to filter context.
- The PBIX opens without repair prompts and refreshes without formula/query errors.
- The workbook Control formulas show no Excel errors.
- Every submitted screenshot is readable and directly supports the stated result.

## Troubleshooting

- If Power BI cannot find the workbook, use **Data source settings > Change Source** and point to the copy in this lab folder.
- If a visual is blank, check data types, relationships, filter context and whether the measure returns BLANK().
- If totals disagree, reconcile row count and grain before changing the DAX.
- If Power BI Service is unavailable, retain the Desktop report evidence and describe the intended publish/dashboard steps for trainer verification.

## Source note

The starter PBIX files come from the approved Microsoft PL-300 learning assets already stored in the supplied course Drive. The Excel scenarios are generated for this WSQ course and incorporate useful legacy sample-data patterns without learner submissions or personal data.

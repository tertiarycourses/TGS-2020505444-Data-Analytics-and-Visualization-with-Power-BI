# Lab 9: Apply Time Intelligence and Scenario Analysis

**Level:** Advanced  
**Alignment:** LO6 · A6  
**Estimated time:** 60 minutes

## Scenario and goal

Use the supplied Excel evidence workbook and Power BI starter to produce: **YTD, prior-period, Top N and what-if analysis with decision commentary**.

## Files in this folder

- `Scenario_Analysis.xlsx` - intake, control and audit-evidence workbook
- `starter.pbix` - clean Power BI starter file from the approved Microsoft learning assets already held in the course Drive
- `README.md` - editable lab guide
- `README.pdf` - printable lab guide

## Before you start

1. Use Power BI Desktop on Windows and work on a copy of `starter.pbix`.
2. Keep this folder structure intact so relative source paths are easier to repair.
3. Do not upload confidential or personal data to the training workspace.
4. Read the workbook Control and Evidence sheets before building.

## Step-by-step

1. Open `starter.pbix`, save a working copy, and import `Scenario_Analysis.xlsx`.
2. Confirm the active relationship from DimDate to FactSales and mark the date table.
3. Create Sales YTD, Sales Prior Year and Sales Growth % measures.
4. Create a Top N parameter and use TOPN logic or a Top N visual filter to rank products.
5. Create bins for order value and use a histogram to inspect distribution.
6. Add a trend line to a scatter chart and state why the relationship is not proof of causation.
7. Use the Analyze feature on one increase or decrease and record the suggested driver.
8. Create a what-if parameter for Discount Adjustment from 0% to 15% in 1% increments.
9. Create Scenario Revenue and Scenario Profit measures that use the selected parameter.
10. Build Actual versus Scenario comparison cards and a sensitivity line chart.
11. Identify one anomaly or outlier and test whether it persists after changing filters.
12. Write a stakeholder note with finding, evidence, limitation and recommended action.

## Evidence to retain

- Saved PBIX working file with your name in the filename
- Screenshot of the relevant query, model, report or Service page
- Completed Excel Evidence sheet
- One finding, the supporting visual/measure, one limitation and one recommended action

## Acceptance criteria

- Date logic is valid; parameters change results; findings state business meaning and limitations.
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

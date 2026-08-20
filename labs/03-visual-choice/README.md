# Lab 3: Choose Visuals for Trends and Correlations

**Level:** Intermediate  
**Alignment:** LO2 · K2 · A2  
**Estimated time:** 45 minutes

## Scenario and goal

Use the supplied Excel evidence workbook and Power BI starter to produce: **A one-page analytical report using fit-for-purpose native visuals**.

## Files in this folder

- `Sales_Trends.xlsx` - intake, control and audit-evidence workbook
- `starter.pbix` - clean Power BI starter file from the approved Microsoft learning assets already held in the course Drive
- `README.md` - editable lab guide
- `README.pdf` - printable lab guide

## Before you start

1. Use Power BI Desktop on Windows and work on a copy of `starter.pbix`.
2. Keep this folder structure intact so relative source paths are easier to repair.
3. Do not upload confidential or personal data to the training workspace.
4. Read the workbook Control and Evidence sheets before building.

## Step-by-step

1. Open `starter.pbix`, save a working copy, and import `Sales_Trends.xlsx`.
2. Read the five stakeholder questions on the `Questions` sheet before adding any visual.
3. Create a clustered bar chart for ranked category comparison and sort by Sales descending.
4. Create a line chart for monthly Sales and use a continuous date axis.
5. Create a scatter chart with Sales on X, Profit on Y, Quantity as size, and Category as legend.
6. Create one KPI or gauge that compares current Sales with Target Sales.
7. Use a matrix where precise product and region values are required.
8. For each visual, replace the generic title with a short insight title that answers its question.
9. Use color consistently: one accent for focus, neutrals for context, and red only for a defined exception.
10. Check axes for misleading truncation and confirm currency/percentage formats.
11. Add a small text box stating one limitation of the comparison or correlation shown.
12. Complete the visual-choice rationale and evidence checklist in the workbook.

## Evidence to retain

- Saved PBIX working file with your name in the filename
- Screenshot of the relevant query, model, report or Service page
- Completed Excel Evidence sheet
- One finding, the supporting visual/measure, one limitation and one recommended action

## Acceptance criteria

- Each visual answers a stated question; encodings are accurate; titles express insight.
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

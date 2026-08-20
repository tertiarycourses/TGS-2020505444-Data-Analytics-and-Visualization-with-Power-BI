# Lab 1: Connect, Inspect and Profile an Excel Dataset

**Level:** Foundation  
**Alignment:** LO1 · K1 · A1  
**Estimated time:** 45 minutes

## Scenario and goal

Use the supplied Excel evidence workbook and Power BI starter to produce: **A profiled query with correct headers, types and documented quality issues**.

## Files in this folder

- `Retail_Intake.xlsx` - intake, control and audit-evidence workbook
- `starter.pbix` - clean Power BI starter file from the approved Microsoft learning assets already held in the course Drive
- `README.md` - editable lab guide
- `README.pdf` - printable lab guide

## Before you start

1. Use Power BI Desktop on Windows and work on a copy of `starter.pbix`.
2. Keep this folder structure intact so relative source paths are easier to repair.
3. Do not upload confidential or personal data to the training workspace.
4. Read the workbook Control and Evidence sheets before building.

## Step-by-step

1. Open `starter.pbix` in Power BI Desktop and save a working copy as `Lab01-<your-name>.pbix`.
2. Select **Home > Get data > Excel workbook** and choose `Retail_Intake.xlsx`.
3. In Navigator, select `Orders`, `Returns`, and `People`; review the preview before selecting **Transform Data**.
4. In Power Query Editor, confirm that the first row is used as headers and that each query has a meaningful name.
5. Turn on **View > Column quality**, **Column distribution**, and **Column profile**.
6. Record null, error, and distinct-value observations in the workbook `Evidence` sheet.
7. Set date, whole-number, decimal, and text data types deliberately; use locale where required.
8. Remove columns that do not support the stated retail questions, but keep all business keys.
9. Rename technical columns only when the new name remains unambiguous and consistent.
10. Select **Close & Apply**, then confirm all three tables appear in Data view.
11. Create a card for total Sales and a table showing Order ID, Customer Name, Sales, and Profit.
12. Save the PBIX and capture the query list, column-profile evidence, and the first report page.

## Evidence to retain

- Saved PBIX working file with your name in the filename
- Screenshot of the relevant query, model, report or Service page
- Completed Excel Evidence sheet
- One finding, the supporting visual/measure, one limitation and one recommended action

## Acceptance criteria

- All required tables load; column quality is reviewed; no unintended errors remain.
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

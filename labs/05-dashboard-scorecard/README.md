# Lab 5: Build an Executive Dashboard and Scorecard

**Level:** Intermediate  
**Alignment:** LO3 · K3 · A3  
**Estimated time:** 45 minutes

## Scenario and goal

Use the supplied Excel evidence workbook and Power BI starter to produce: **A Sales Monitoring dashboard and KPI scorecard in Power BI Service**.

## Files in this folder

- `Executive_KPIs.xlsx` - intake, control and audit-evidence workbook
- `starter.pbix` - clean Power BI starter file from the approved Microsoft learning assets already held in the course Drive
- `README.md` - editable lab guide
- `README.pdf` - printable lab guide

## Before you start

1. Use Power BI Desktop on Windows and work on a copy of `starter.pbix`.
2. Keep this folder structure intact so relative source paths are easier to repair.
3. Do not upload confidential or personal data to the training workspace.
4. Read the workbook Control and Evidence sheets before building.

## Step-by-step

1. Open `starter.pbix`, save a working copy, and import `Executive_KPIs.xlsx`.
2. Create or verify measures for Sales, Profit, Margin %, Target Sales, and Target Attainment %.
3. Build a report page with one executive outcome row and one driver/exceptions row.
4. Publish the working report to the training workspace in Power BI Service.
5. Create a dashboard named `Sales Monitoring - <your initials>`.
6. Pin the Sales, Profit and Margin visuals as individual tiles.
7. Pin the decision page as a live page only if its interactions are needed for monitoring.
8. Resize and arrange tiles from outcome to drivers to exceptions.
9. Create a scorecard with at least two goals, targets, owners and status logic.
10. Configure an alert on one supported KPI tile and document the owner and response action.
11. Review the mobile layout and move only the essential monitoring signals above the fold.
12. Capture the report, dashboard, scorecard and mobile layout as Evidence; do not expose confidential workspace data.

## Evidence to retain

- Saved PBIX working file with your name in the filename
- Screenshot of the relevant query, model, report or Service page
- Completed Excel Evidence sheet
- One finding, the supporting visual/measure, one limitation and one recommended action

## Acceptance criteria

- Tiles and targets are current, decision-focused and traceable to the report.
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

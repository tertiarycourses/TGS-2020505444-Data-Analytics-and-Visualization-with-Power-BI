# Lab 10: Deliver the GlobalTech Sales Performance Cockpit

**Level:** Capstone  
**Alignment:** LO1–LO6 · K1–K5 · A1–A6  
**Estimated time:** 60 minutes

## Scenario and goal

Use the supplied Excel evidence workbook and Power BI starter to produce: **A stakeholder-ready PBIX report, dashboard evidence and QA checklist**.

## Files in this folder

- `GlobalTech_Capstone.xlsx` - intake, control and audit-evidence workbook
- `starter.pbix` - clean Power BI starter file from the approved Microsoft learning assets already held in the course Drive
- `README.md` - editable lab guide
- `README.pdf` - printable lab guide

## Before you start

1. Use Power BI Desktop on Windows and work on a copy of `starter.pbix`.
2. Keep this folder structure intact so relative source paths are easier to repair.
3. Do not upload confidential or personal data to the training workspace.
4. Read the workbook Control and Evidence sheets before building.

## Step-by-step

1. Open `starter.pbix`, save a working copy as `GlobalTech-Capstone-<your-name>.pbix`, and import `GlobalTech_Capstone.xlsx`.
2. Read the stakeholder brief and convert each question into a required visual or interaction.
3. Transform the source tables and document at least four meaningful Applied Steps.
4. Build a star schema with validated one-to-many relationships and a marked date table.
5. Create governed measures for Sales, Profit, Profit Margin, Sales % All Region, Target Attainment and YTD Growth.
6. Create an Executive Overview page with outcome KPIs, a country/category comparison and an exception list.
7. Create a Regional Analysis page with a map or region comparison, matrix and drillthrough path.
8. Create a Product Analysis page with trend, Top N and contribution evidence.
9. Add slicers, reset navigation, tooltips and intentional cross-filter/highlight interactions.
10. Publish to the training workspace and create the `Sales Monitoring` dashboard with report links intact.
11. Complete the workbook Acceptance and Evidence sheets, including one limitation and one recommended action.
12. Run the final QA: refresh, relationships, totals, visual accuracy, accessibility, interactions, mobile layout and privacy.

## Evidence to retain

- Saved PBIX working file with your name in the filename
- Screenshot of the relevant query, model, report or Service page
- Completed Excel Evidence sheet
- One finding, the supporting visual/measure, one limitation and one recommended action

## Acceptance criteria

- The solution meets all six outcomes, answers stakeholder questions and passes the evidence checklist.
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

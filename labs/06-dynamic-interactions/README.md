# Lab 6: Create Dynamic Interactions and Navigation

**Level:** Intermediate  
**Alignment:** LO4 · K4 · A4  
**Estimated time:** 45 minutes

## Scenario and goal

Use the supplied Excel evidence workbook and Power BI starter to produce: **An interactive report with slicers, drillthrough, bookmarks and tested interactions**.

## Files in this folder

- `Campaign_Performance.xlsx` - intake, control and audit-evidence workbook
- `starter.pbix` - clean Power BI starter file from the approved Microsoft learning assets already held in the course Drive
- `README.md` - editable lab guide
- `README.pdf` - printable lab guide

## Before you start

1. Use Power BI Desktop on Windows and work on a copy of `starter.pbix`.
2. Keep this folder structure intact so relative source paths are easier to repair.
3. Do not upload confidential or personal data to the training workspace.
4. Read the workbook Control and Evidence sheets before building.

## Step-by-step

1. Open `starter.pbix`, save a working copy, and import `Campaign_Performance.xlsx`.
2. Create a summary page with Channel, Campaign, Spend, Leads and Revenue visuals.
3. Add a date slicer and a Channel slicer; show the current selection clearly.
4. Configure one source visual to cross-filter a target and another to cross-highlight a comparison.
5. Disable an interaction where responding would mislead or create visual noise.
6. Create a hierarchy for Channel > Campaign > Creative and test all drill states.
7. Create a drillthrough page for Campaign detail and add a Back button.
8. Create a report-page tooltip with conversion rate, cost per lead and return on ad spend.
9. Create bookmarks for Executive view, Analyst view and Reset filters.
10. Add buttons for the bookmarks and use consistent selected/hover states.
11. Add a field parameter that switches the main comparison between Revenue, Leads and Spend.
12. Run the interaction test matrix in the workbook and fix every unexpected state.

## Evidence to retain

- Saved PBIX working file with your name in the filename
- Screenshot of the relevant query, model, report or Service page
- Completed Excel Evidence sheet
- One finding, the supporting visual/measure, one limitation and one recommended action

## Acceptance criteria

- Every interaction is intentional; drill paths work; reset navigation restores the default state.
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

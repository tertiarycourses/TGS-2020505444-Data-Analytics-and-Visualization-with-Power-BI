# Lab 7: Model a Star Schema and Date Dimension

**Level:** Advanced  
**Alignment:** LO5 · K5 · A5  
**Estimated time:** 45 minutes

## Scenario and goal

Use the supplied Excel evidence workbook and Power BI starter to produce: **A semantic model with fact/dimension relationships and a marked date table**.

## Files in this folder

- `Star_Schema.xlsx` - intake, control and audit-evidence workbook
- `starter.pbix` - clean Power BI starter file from the approved Microsoft learning assets already held in the course Drive
- `README.md` - editable lab guide
- `README.pdf` - printable lab guide

## Before you start

1. Use Power BI Desktop on Windows and work on a copy of `starter.pbix`.
2. Keep this folder structure intact so relative source paths are easier to repair.
3. Do not upload confidential or personal data to the training workspace.
4. Read the workbook Control and Evidence sheets before building.

## Step-by-step

1. Open `starter.pbix`, save a working copy, and import every table from `Star_Schema.xlsx`.
2. In Power Query, confirm each table grain and ensure dimension keys are unique.
3. In Model view, place `FactSales` in the center and the Date, Product, Customer and Region dimensions around it.
4. Create one-to-many relationships from each dimension key to its matching fact foreign key.
5. Use single cross-filter direction unless the scenario documents a tested exception.
6. Mark `DimDate` as the date table using its Date column.
7. Create a Month Sort column and sort Month Name by Month Number.
8. Create a Region > Country > Store hierarchy and a Product Category > Product hierarchy.
9. Hide surrogate keys and other technical columns from Report view.
10. Set currency, percentage, date, and default summarization properties.
11. Use the Orphans sheet to validate that every fact foreign key finds one dimension row.
12. Build a small matrix and slicer test page to prove totals and filter paths are correct.

## Evidence to retain

- Saved PBIX working file with your name in the filename
- Screenshot of the relevant query, model, report or Service page
- Completed Excel Evidence sheet
- One finding, the supporting visual/measure, one limitation and one recommended action

## Acceptance criteria

- Relationships use correct keys/cardinality; filters flow predictably; model ambiguity is zero.
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

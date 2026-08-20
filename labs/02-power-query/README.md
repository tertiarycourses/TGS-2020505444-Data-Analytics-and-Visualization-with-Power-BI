# Lab 2: Clean, Transform, Append and Merge

**Level:** Foundation  
**Alignment:** LO1 · K1 · A1  
**Estimated time:** 45 minutes

## Scenario and goal

Use the supplied Excel evidence workbook and Power BI starter to produce: **A repeatable Power Query transformation pipeline with an audit trail**.

## Files in this folder

- `Retail_Quality_Issues.xlsx` - intake, control and audit-evidence workbook
- `starter.pbix` - clean Power BI starter file from the approved Microsoft learning assets already held in the course Drive
- `README.md` - editable lab guide
- `README.pdf` - printable lab guide

## Before you start

1. Use Power BI Desktop on Windows and work on a copy of `starter.pbix`.
2. Keep this folder structure intact so relative source paths are easier to repair.
3. Do not upload confidential or personal data to the training workspace.
4. Read the workbook Control and Evidence sheets before building.

## Step-by-step

1. Open `starter.pbix`, save a working copy, and import `Retail_Quality_Issues.xlsx` through **Transform Data**.
2. Rename the imported query `Sales_Staging` and inspect Applied Steps before adding transformations.
3. Remove the two note rows above the actual header and promote the remaining first row as headers.
4. Trim and clean text columns; standardize region values so `South East`, `SE`, and `Southeast` become `Southeast`.
5. Replace blank discount values only after deciding whether blank means zero or unknown; document the choice.
6. Set Order Date using the correct locale and isolate conversion errors rather than deleting them silently.
7. Define the business key, identify duplicate records, and keep the intended surviving record.
8. Unpivot the monthly target columns into `Month` and `Target`.
9. Append the `Late_Arrivals` query to the cleaned sales query and reconcile row counts.
10. Merge the `Region_Manager` table with a left outer join; expand only Manager and Territory.
11. Create a conditional column for Margin Band using the thresholds in the workbook `Control` sheet.
12. Review the generated M in Advanced Editor and add a short comment above the business-rule step.
13. Close & Apply, then validate the Control totals and complete the Evidence sheet.

## Evidence to retain

- Saved PBIX working file with your name in the filename
- Screenshot of the relevant query, model, report or Service page
- Completed Excel Evidence sheet
- One finding, the supporting visual/measure, one limitation and one recommended action

## Acceptance criteria

- Headers, types, nulls and duplicates are corrected; append and merge row counts reconcile.
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

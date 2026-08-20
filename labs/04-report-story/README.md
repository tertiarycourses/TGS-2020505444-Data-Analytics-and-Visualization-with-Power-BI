# Lab 4: Design an Accessible Report Story

**Level:** Intermediate  
**Alignment:** LO2 · K2 · A2  
**Estimated time:** 45 minutes

## Scenario and goal

Use the supplied Excel evidence workbook and Power BI starter to produce: **A polished report page with hierarchy, theme, tooltips and accessible navigation**.

## Files in this folder

- `Customer_Experience.xlsx` - intake, control and audit-evidence workbook
- `starter.pbix` - clean Power BI starter file from the approved Microsoft learning assets already held in the course Drive
- `README.md` - editable lab guide
- `README.pdf` - printable lab guide

## Before you start

1. Use Power BI Desktop on Windows and work on a copy of `starter.pbix`.
2. Keep this folder structure intact so relative source paths are easier to repair.
3. Do not upload confidential or personal data to the training workspace.
4. Read the workbook Control and Evidence sheets before building.

## Step-by-step

1. Open `starter.pbix`, save a working copy, and import `Customer_Experience.xlsx`.
2. Apply the provided `Theme` color roles consistently across the page.
3. Create a page title that states the decision and a subtitle that states the active period.
4. Arrange KPI cards first, trend evidence second, and diagnostic detail last in the reading order.
5. Create a tooltip page showing response volume, satisfaction score, and verbatim-comment count.
6. Add a drill hierarchy from Region to Store and test drill down, expand, and drill up.
7. Add alt text to every meaningful visual and mark decorative elements as decorative where supported.
8. Open **View > Selection** and **Tab order**; place objects in a logical keyboard reading sequence.
9. Check text and data colors for sufficient contrast and ensure status is never shown by color alone.
10. Use whitespace and alignment instead of borders around every object.
11. Test the page at 100% and Fit to page, then capture a screenshot for Evidence.
12. Ask a peer to state the main finding in ten seconds; revise if their answer differs from the intended message.

## Evidence to retain

- Saved PBIX working file with your name in the filename
- Screenshot of the relevant query, model, report or Service page
- Completed Excel Evidence sheet
- One finding, the supporting visual/measure, one limitation and one recommended action

## Acceptance criteria

- The page has a clear reading order, consistent formatting, alt text and no misleading scale.
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

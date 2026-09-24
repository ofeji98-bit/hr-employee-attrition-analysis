# HR Employee Attrition Analysis — H&S Pharmaceuticals

**Tools:** Excel (PivotTables, IFS/DATEDIF formulas, Slicers)

## Overview
Analysis of a 12.24% attrition rate among 1,470 employees, identifying the key drivers behind who leaves and when.

## Key Findings
- The 2021 spike (63 leavers) was concentrated in newer, junior R&D employees earning in the lowest salary band
- Sales has the highest departmental attrition rate (15.47%)
- 75 employees left within their first year alone — attrition is heavily concentrated in early tenure
- Key drivers: low salary band, no stock options, low environmental/job satisfaction, poor work-life balance

## Methodology
- Replaced numeric performance/satisfaction codes with labels using `IFS()`
- Reconciled attrition status against termination type using `IFS()`
- Built tenure and age-group buckets using `DATEDIF()` and `IFS()`
- Built PivotTables and a two-page dashboard with Age Group, Department, Gender, and Job Role slicers

## Files
- `documentation.docx` — full write-up (methodology, findings, recommendations)
- `dashboard_1.png`, `dashboard_2.png` — dashboard screenshots

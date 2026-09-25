# Region Performance — Sales vs. Profit Analysis

## Description
Compare sales performance across the five U.S. regions in the Superstore dataset using an Excel PivotTable and PivotChart.

## Objective
Practice grouping and comparison in Excel.

## Tools
- Microsoft Excel (PivotTable, PivotChart)

## Dataset
Superstore — `Sales_Data.xlsx`, 3,000 order-level rows (Order ID, Region, Sales, Profit, etc.)

## Method
1. Loaded `Sales Data` sheet into a PivotTable.
2. **Rows:** Region
3. **Values:** Sum of Sales, Sum of Profit
4. Inserted a clustered column PivotChart from the table.

## Results

| Region | Sales ($) | Profit ($) | Profit Margin | Sales Rank | Profit Rank |
|--------|----------:|-----------:|---------------:|:----------:|:-----------:|
| West    | 676,239.46 | 109,695.07 | 16.22% | 1 | 3 |
| South   | 670,167.23 | 128,991.62 | 19.25% | 2 | 1 |
| East    | 669,410.86 | 113,362.31 | 16.93% | 3 | 2 |
| North   | 585,279.26 |  98,426.49 | 16.82% | 4 | 4 |
| Central | 539,911.95 |  90,384.08 | 16.74% | 5 | 5 |
| **Total** | **3,141,008.76** | **540,859.57** | **17.22%** | | |

*(Figures independently verified against the 3,000-row source sheet — they match exactly.)*

## Key Finding
**West sells the most, but South is the most profitable region — and by far the most efficient.** South converts sales to profit at 19.25%, nearly 3 points above every other region, while West (the sales leader) has the weakest margin at 16.22%. Ranking by revenue alone would send attention to the wrong region.

## Interview Questions

**Q: Why compare profit with sales?**
Sales measures scale; profit measures how efficiently that scale is converted into money the business keeps. A region can lead on revenue and still be a weaker contributor to the bottom line. Looking at both — and at margin — prevents optimizing for the wrong metric.

**Q: How would you rank regions?**
It depends on the goal:
- **By Sales** — for market size / reach
- **By Profit** — for bottom-line contribution
- **By Profit Margin** — for operational efficiency
Presenting all three (as in the table above) gives a fuller picture than any single ranking.



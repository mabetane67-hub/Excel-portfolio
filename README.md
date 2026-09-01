# Excel-portfolio

## Projects

### Bike Sales Dashboard (Excel)

A pivot-table-driven dashboard exploring who buys bikes and why, built from a 1,000-row customer dataset in Excel.
<img width="1232" height="952" alt="image" src="https://github.com/user-attachments/assets/f92c4dc8-2e8b-486d-813c-d4931074dd29" />

What's in this workbook: 

bike_buyers:	Raw source data (1,000 customers, 13 attributes)
Working Sheet:	Cleaned copy of the data plus an engineered Age brackets column (nested IFS formula: Adolescent 0-30 / Middle age 31-54 / Old 55+)
Pivot table:	Three PivotTables answering specific questions about the data
Dashboard:	The three PivotCharts combined into one view, with slicers to filter by Education and Region

Questions this dashboard answers:

-Does income differ between buyers and non-buyers? 

-Does commute distance affect the chance someone buys a bike?

-Which age group buys the most?

Key findings (full 1,000-customer dataset)

Income: Buyers had noticeably higher average income than non-buyers, in both genders — male buyers averaged $60,124 vs $56,208 for male non-buyers; female buyers averaged $55,774 vs $53,440 for female non-buyers.

Commute distance: Purchase rate is highest for very short commutes — 55% of people with a 0-1 mile commute bought a bike (200 of 366), compared to just 30% of people commuting more than 10 miles (33 of 111). Shorter commute, more likely to bike.

Age: Middle-age customers (31-54) are the only group where buyers outnumber non-buyers (388 vs 331), and they make up 72% of the customer base. Customers 55+ buy at a much lower rate (54 of 171, ~32%).

Tools & techniques:
Excel PivotTables · PivotCharts · nested IFS formula . Slicers for interactive filtering.

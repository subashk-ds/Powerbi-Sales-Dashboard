# Powerbi-Sales-Dashboard
Interactive Power BI sales dashboard with DAX measures, slicers, and KPI cards

# Power BI Sales Performance Dashboard

An interactive sales dashboard built in Power BI Desktop analyzing 
50 sales transactions across 5 regions and 5 salespersons.

## Dashboard Features
- Total Revenue KPI card
- High Performance Revenue KPI card (DAX CALCULATE measure)
- Revenue by Region bar chart (with % of total tooltip)
- Top Salesperson performance column chart
- Interactive Region slicer (filter entire dashboard by region)
- Interactive Performance slicer (High/Low filter)

## DAX Measures Built
| Measure | Formula Logic |
|---------|--------------|
| Total Revenue | SUM of all revenue |
| High Performance Revenue | CALCULATE with Performance filter |
| Region % of Total | DIVIDE with ALL() to ignore filters |

## Key Insights
- Mumbai is the top revenue region (32% of total)
- Karthik leads overall salesperson performance
- High performance transactions account for ~1M of 4.6M total revenue

## Tools Used
Power BI Desktop

## Data Source
50-row sales dataset (same dataset used in Excel project)
Excel project: github.com/subashk-ds/excel-sales-analysis

## Author
Subash K | [LinkedIn](https://linkedin.com/in/subash-ds)

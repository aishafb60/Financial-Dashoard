# Financial-Dashoard
## Project Overview
This dashboard analyzes historical stock prices using the following columns:
- `date`
- `open`
- `high`
- `low`
- `close`
- `volume`
- `name`

It provides interactive visualizations to help stakeholders explore stock trends and trading activity over time.

## Data Source
The dataset was sourced from (Google Sheets/Kaggle link). It contains historical stock prices for multiple companies.

## Steps & Methodology
1. Imported dataset into Looker Studio via Google Sheets.
2. Created KPIs (Scorecards):
   - Current Price (close) → MAX
   - Highest Price (high) → MAX
   - Lowest Price (low) → MIN
   - Average Closing Price (close) → AVERAGE
   - Total Volume (volume) → SUM
3. Added interactive visualizations:
   - **Time Series Chart** for closing price trend.
   - **Bar Chart** comparing average closing prices per company.
   - **Pie Chart** showing volume distribution among companies.
4. Added Filters:
   - Drop-down list → `name` (company)
   - Date Range Control → `date`
5. Added Insights Text Box summarizing key trends.

## Dashboard Screenshot


## Key Insights
- Stocks fluctuate between high and low prices over the selected period.
- Average closing price highlights top-performing companies.
- Volume distribution shows dominant stocks in trading activity.

## Live Dashboard Link
[Click here to view the interactive dashboard](https://lookerstudio.google.com/reporting/438b7a7a-d60a-4ca8-87c7-1b027be6bdbf)


## Assumptions & Limitations
- Data limited to the dataset; external market events are not considered.
- Analysis is based on historical stock prices; future performance is not predicted.

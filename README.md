# 13-Week-Cash-Flow-Forecast
Built a 13-week cash flow forecasting model in Excel to monitor weekly liquidity, project cash inflows and outflows, and evaluate short term financial stability through dynamic assumptions and scenario analysis.

# 📊 13-Week Cash Flow Forecast Model
## Overview
I built a dynamic 13-week cash flow forecasting model in Excel to monitor weekly liquidity, project cash inflows and outflows, and support short-term financial planning.

## Objective
Through this project, I aimed to:
* Analyze short-term cash position
* Forecast weekly liquidity trends
* Understand how receivables and payables timing impacts cash flow

## What I Did
* Structured raw financial data into a clean and usable format
* Categorized transactions into inflows and outflows
* Used AR and AP aging schedules to estimate timing of cash movements
* Built a dynamic forecast that updates automatically with input changes
* Added error checks to maintain model consistency

## How the Model Works
* I organized raw data in a dedicated input sheet
* Mapped transactions into relevant categories
* Used AR and AP schedules to determine when cash is actually received or paid
* Applied Excel functions such as:
  * SUMIFS
  * INDEX-MATCH
  * SEARCH

The model calculates:
* Beginning Cash Balance
* Net Cash Movement
* Ending Cash Balance

## Key Insight
While building this model, I realized that profitability does not always translate to liquidity.
In this case, the cash balance drops to around ~$43K in the early weeks due to timing differences between inflows and outflows, before recovering later. This highlights how businesses can face short-term liquidity pressure despite stable operations.

## File Structure
* Summary → Final output and cash trend
* Forecast → Core weekly calculations
* Raw Data → Input data
* AR Aging → Receivables timing
* AP Aging → Payables timing
* Transaction Mapping → Categorization logic
* Error Checking → Validation checks

## Tools Used
* Microsoft Excel
* Financial Modeling Techniques
* Cash Flow Forecasting

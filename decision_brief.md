# Decision Brief: Week 1 Retail Sales Snapshot

## Business problem
A retail manager needs a concise baseline view of order revenue and how it varies over the observed months and across regions, before deciding where to focus a follow-up review.

## Stakeholder
The retail operations or commercial manager responsible for reviewing sales performance.

## Decision
Use the observed monthly and regional revenue patterns to select a region or period for a targeted follow-up on product availability and sales activity. This analysis informs where to investigate; it does not establish what caused the observed differences.

## Unit of analysis
One row represents one retail order/transaction (one unique `OrderID`), containing a customer, date, region, channel, product, quantity, unit price, and recorded revenue.

## Analytical task
Primarily **descriptive**: summarize what revenue was recorded and how it is distributed by month and region.

## Three KPIs
- **Total revenue:** sum of `Revenue_KES` = **KES 3,206,450**. This is the recorded revenue across all 300 orders.
- **Number of transactions:** distinct count of `OrderID` = **300**. Each unique ID is counted once.
- **Average transaction value:** total revenue ÷ transactions = **KES 10,688.17** per order. This is the mean recorded revenue per order.

## Initial findings
Monthly revenue peaked in **2026-03** at **KES 1,367,650** and was lowest in **2026-02** at **KES 909,900** (50.3% lower than the peak). **Kisumu** recorded the highest regional revenue, **KES 878,050**. These are descriptive comparisons, not explanations of why the differences occurred.

## Limitation
The dataset covers only three months and contains no costs, margins, inventory, promotions, or market context. Revenue alone cannot establish profitability, causes of changes, or future performance; the findings should guide follow-up questions rather than be treated as causal or predictive conclusions.

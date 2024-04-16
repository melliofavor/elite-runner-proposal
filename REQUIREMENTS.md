## Needs
- The need to improve Runners' performance metrics.
- The need to link the improvement of internal operations (specifically Runners' performance) to the broader business objective of enhancing service quality for both customers and merchants.

## Problem Statement
- The current performance metrics of Runners may not be at an optimal level, which impacts the quality of service provided to customers and merchants.

## Solution
Implement an Incentive Program for Runners that offers rewards and benefits based on their performance metrics, thereby incentivizing Runners to improve their individual performance. This solution is intended to lead to better quality service through enhanced internal operations.

### Main Features

- **Individual Performance Dashboard:** in a gamification strategy aimed at enhancing workplace performance, specifically in the context of improving Runners' performance metrics as part of an Incentive Program.
- **Benefits:** are designed as additional compensations that Runners can earn based on their performance levels and metrics. These benefits are non-wage compensation.
- **Rewards:** are immediate and tangible incentives provided to Runners based on achieving specific performance goals. 


### Individual Performance Dashboard
The dashboard presents key performance indicators (KPIs) that align with a gamification strategy.

| KPI              | Type of Calculation | Periodicity            | Evaluation Time Span                     |
|------------------|---------------------|------------------------|------------------------------------------|
| Acceptance Rate  | Ratio               | Per 100 requests       | Last 100 requests or rolling window of 100 requests |
| Completion Rate  | Ratio               | Per 100 completions    | Last 100 completions or rolling window of 100 completions |
| Runner Rating    | Simple Average      | Post-interaction       | Continuous (all-time) with periodic review (e.g., monthly) |
| Monthly Favors   | Count               | Fixed interval         | Monthly                                  |


**Acceptance Rate:** Calculated as a ratio of accepted favors to total favors offered to the last 100 requests. This focuses on the most recent performance, providing a snapshot of current behavior over a set number of recent opportunities.

**Completion Rate:** This is a ratio of completed favors to accepted favors to the last 100 accepted requests. This measure offers an up-to-date view of efficiency and reliability, limited to a recent set number of engagements.

**Runner Rating:** Calculated using a simple average of all post-interaction ratings given to the Runner. This rating is continuous and accumulates over time but can be reviewed periodically (like monthly) to track changes in performance quality.

**Monthly Favors:** A count of the total number of favors completed within a monthly period. This fixed interval measurement provides insight into the Runner's capacity and activity level for the month.
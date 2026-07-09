# loan-securizationa-
Built a Securitisation Risk Assessment Dashboard using Microsoft Power BI, Excel Power Pivot, and advanced DAX with assumed SAP/ERP banking data.Built a Securitisation Risk Assessment Dashboard using Microsoft Power BI, Excel Power Pivot, and advanced DAX with assumed SAP/ERP banking data.

my final dashbard:
https://github.com/sayedahaseena9-sys/loan-securizationa-/blob/main/Auto%20Loan%20Securitization%20Dashboard.pbit

my excel work:
## 1.Executive portfolio dashboard:https://github.com/sayedahaseena9-sys/loan-securizationa-/blob/main/Executive%20portfolio%20dashboard.png
KPI Cards
Loan Balance
ECL
Default Rate
Recovery Rate
Portfolio Risk Score
Loan Purpose
Employment Type
Region
Vehicle Type
Channel Analysis
State-wise Exposure
Balance Distribution

## Insights:
1.The portfolio has a total outstanding balance of 317.79M across 500 loans, with an estimated ECL of 11.66M.
2.The average CIBIL score (739) indicates generally good borrower credit quality.
3.SUVs and MUVs contribute the highest loan exposure, making them the largest risk segments.
4.Nearly 86% of loans remain in IFRS Stage 1, suggesting most borrowers are performing well.
5.Chhattisgarh, Gujarat, and Goa have the highest outstanding balances and should be monitored closely.
6.Most loans are issued for new vehicle purchases, indicating new vehicle financing dominates the portfolio.

## 2.Portfolio risk dashboard:https://github.com/sayedahaseena9-sys/loan-securizationa-/blob/main/Portfolio%20risk%20dashboard.png
kpi cards
average EAD
average PD
average LGD
IFRS stage distribution
cibil score
LTV current

## Insights
1.Stage 1 accounts dominate, indicating a healthy loan portfolio with limited credit deterioration.
2.The portfolio's total expected loss is 0.88M, while recoveries amount to 0.40M, reducing net credit losses.
3.Only 1.8% of loans are in default, demonstrating strong portfolio quality.
4.Average PD (0.08) and LGD (0.50) indicate moderate expected credit risk.
5.The CIBIL score distribution is concentrated between 650–800, confirming that most borrowers have acceptable creditworthiness.

## 3.Deliquency dashborad:https://github.com/sayedahaseena9-sys/loan-securizationa-/blob/main/Deliquency%20dashboard.png
DPD Distribution
Roll Rate
Cure Rate
Write-offs
Repossessions

## Insights
1.Stage 1 accounts dominate, indicating a healthy loan portfolio with limited credit deterioration.
2.The portfolio's total expected loss is 0.88M, while recoveries amount to 0.40M, reducing net credit losses.
3.Only 1.8% of loans are in default, demonstrating strong portfolio quality.
4.Average PD (0.08) and LGD (0.50) indicate moderate expected credit risk.
5.The CIBIL score distribution is concentrated between 650–800, confirming that most borrowers have acceptable creditworthiness.

## 4.IFRS 9 and ECL dashboard:https://github.com/sayedahaseena9-sys/loan-securizationa-/blob/main/IFRS%209%20%26%20ECL%20dashboard.png
Stage Distribution
PD
LGD
EAD
Expected Credit Loss
Risk Matrix
Scatter (PD vs LGD)
waterfall value

## Insights
1.Stage 1 exposure (4.14B) significantly exceeds Stage 2 and Stage 3 exposures, reflecting a stable portfolio.
2.Stage 3 ECL provisions are the highest, despite lower exposure, due to increased credit risk.
3.States such as Chhattisgarh and Kerala require higher provisions because of elevated expected losses.
4.Scatter analysis shows higher PD values lead to larger ECL provisions, validating the IFRS 9 model.

## 5.Vintage analysis dashboard:https://github.com/sayedahaseena9-sys/loan-securizationa-/blob/main/Vintage%20analysis%20dashboard.png
Vintage Curve
Monthly Default Trend
Cumulative Loss
marginloss trend
cumulative recoveries

## Insights
1.Pool balance declines steadily over time due to scheduled repayments and loan amortization.
2.Cumulative net losses increase during the middle of the portfolio life before stabilizing.
3.Current 30+ DPD delinquency gradually decreases, indicating improvement in borrower repayment behavior.
4.Recovery amounts increase before slowing toward portfolio maturity.
5.Older loan vintages demonstrate higher cumulative losses than recently originated loans.

## 6.Monthly loss dashboard:https://github.com/sayedahaseena9-sys/loan-securizationa-/blob/main/Monthly%20loss%20dashboard.png
gross loss vs recoveries
payment trend
monthly default trend
net loss trend

## Insights
1.Portfolio balance decreased from 6.19B to 6.01B, reflecting regular repayments.
2.Recoveries of 4.43M partially offset gross losses of 12.22M, resulting in a net loss of 7.78M.
3.Collection efficiency remains positive, indicating effective servicing performance.
4.Monthly default rates remain relatively stable with one temporary spike that warrants further investigation.
5.Prepayments fluctuate throughout the year, affecting cash flow timing for investors.

## 7.Stress testing dashboard:https://github.com/sayedahaseena9-sys/loan-securizationa-/blob/main/Stress%20testing%20dashboard.png
Scenario Slicer
Base Case
Moderate
Severe
Stressed ECL

## Insights
1.Base and stressed ECL values remain close under the current assumptions, indicating portfolio resilience.
2.Compact SUVs experience the highest stressed ECL under adverse scenarios.
3.Severe scenarios generate the largest increase in expected credit losses.
4.Higher PD values combined with elevated LGD significantly increase portfolio risk.
5.Stress testing identifies vehicle types and regions most sensitive to adverse economic conditions.

## 8.Waterfall analysis dashboard:https://github.com/sayedahaseena9-sys/loan-securizationa-/blob/main/Waterfall%20analysis%20dashboard.png
Opening Balance
Defaults
Recoveries
Write-offs
Closing Balance
Waterfall Chart
Monthly Waterfall Trend

## Insights
1.Beginning balance of 6.19B reduces to 6.01B after scheduled repayments, losses, recoveries, and collections.
2.Collections of 224.31M represent the largest positive cash inflow during the reporting period.
3.Gross losses are partially offset by 4.43M recoveries, reducing the portfolio's net loss.
4.Waterfall analysis clearly illustrates how each cash flow component impacts the final portfolio balance.

## 9.Investor reporting dashboard:https://github.com/sayedahaseena9-sys/loan-securizationa-/blob/main/Investor%20reporting%20dashboard.png
Pool Performance
Default %
Recovery %
Yield
Cash Collections
Remaining Principal
Rating Distribution
Investor KPIs

## Insights
1.Pool factor of 0.68 indicates approximately 68% of the original pool balance remains outstanding.
2.Collections consistently exceed recoveries, supporting stable investor cash flows.
3.Vintage performance indicates newer pools are outperforming older loan cohorts.
4.Delinquency remains concentrated in the Current bucket, demonstrating good overall portfolio quality.
5.Excess spread remains positive, providing additional protection against future credit losses.

## 10.Securitization risk arena dashboard:https://github.com/sayedahaseena9-sys/loan-securizationa-/blob/main/Securitization%20risk%20arena%20dashboard.png
Scenario Selector
Risk Meter
Portfolio Health Score
Crisis Timeline
Loss Gauge
Stress Level Indicator
Leaderboard
Risk Challenge Cards
Waterfall Impact
Portfolio Survival Score
Bucket Movement
Monthly Delinquency Trend

## InsightsThe portfolio maintains a Risk Score of 17, corresponding to a Safe portfolio status.
1.Stage 1 loans contribute the majority of portfolio exposure, indicating strong asset quality.
2.Vehicle type analysis shows SUVs and Compact SUVs contribute the highest risk exposure.
3.Recoveries consistently exceed defaults in most reporting periods, improving portfolio resilience.
4.Interactive scenario controls allow analysts to evaluate how changes in PD, LGD, recovery rates, interest rates, and vehicle prices affect ECL and overall portfolio risk.

## Overall project conclusion
The analysis indicates that the securitised loan portfolio is financially stable, with the majority of loans classified as IFRS Stage 1, a low default rate (1.8%), and a moderate Expected Credit Loss (11.66M) relative to the portfolio size. While certain regions and vehicle segments exhibit higher risk concentrations, positive recovery performance, effective collections, and favorable stress-testing results suggest the portfolio is resilient under current assumptions. Continuous monitoring of delinquency trends, Stage 2 migrations, and high-risk segments will help maintain portfolio quality and support informed investor and risk management decisions.


# Financial Market Stress Simulation

Financial market stress simulation using Monte Carlo simulations, sensitivity analysis, and macro-financial indicators.

The idea behind this project is to model financial stress in the U.S. market and simulate how the risk of a severe market correction changes under different economic and financial conditions.

## Main Questions

- How does the risk of a severe correction in the U.S. market change when shocks occur in credit conditions, interest rates, financial conditions, and economic activity?

- Does copper provide additional useful information when estimating and simulating periods of financial stress?

## What do we want to model?

We want to model the state of the financial environment and use it to estimate the risk of a severe correction in the S&P 500.

From there, we can simulate different scenarios and observe how that risk changes when one or several financial indicators are affected.

The main indicators considered are:

- Credit Spread
- Financial Conditions Index
- Yield Curve
- 10-Year Treasury Yield
- Copper

The S&P 500 will be used as the reference for market corrections. Initially, a severe correction will be defined as a drawdown of around 15% over a three-month period.

## Approach

Historical data will first be used to understand the relationship between these indicators and periods of market stress.

Then, Monte Carlo simulation, sensitivity analysis, and stress scenarios will be used to explore questions such as:

- What happens if credit spreads increase sharply?
- What if financial conditions tighten while Treasury yields rise?
- Which variables have the greatest effect on estimated market risk?
- Does adding copper change the results in a meaningful way?

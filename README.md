# Constant Proportion Portfolio Insurance
Portfolio risk management using diligent asset allocation strategy to limit downside risk   

---

## Summary
The constant proportion portfolio insurance is an asset allocation strategy between a risky asset and a safe asset.  The portfolio is rebalanced at regular periods (eg: monthly) with a primary objective of protecting downside risk, minimising the amount of maximum drawdown the portfolio is exposed to.

This analysis compares the portfolio performance between a portfolio having 100% exposure to a risk asset and a portfolio with a CPPI allocation strategy.

## CPPI Strategy
1. Let TA be the total asset for investment at the beginning of the strategy
2. Let PV be the portfolio value at any point in time of the investment period
3. Set a floor F (in percentage terms) how much of TA to protect
4. Cushion C will be the maximum amount of money you are willing to lose (C = PV - F x TA)
5. Depending on your risk appetite, set a multipler M to determine the amount of money to invest in risky asset RA
6. Amount to invest in RA = M x C
7. Amount to invest in safe asset SA = PV - RA
8. Repeat the strategy every month by taking reference how much PV is left in your investment

## Notebook
- https://github.com/edgetrader/constant-proportion-portfolio-insurance/blob/master/notebook/cppi.ipynb
- https://github.com/edgetrader/constant-proportion-portfolio-insurance/blob/master/notebook/interactive-cppi.ipynb (Download the jupyter notebook and run locally to play with the parameters of the CPPI strategies)

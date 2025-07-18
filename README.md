# Equity-Factor-Allocation-With-Index-Funds
The goal of this project was to find the optimal but simple allocation to various factor indexes in the equity market for personal use.

The ideas of the project in logical order:
- What is our investment-goal? The ivestment-horizon is between 25 to 30 years. We want a (semi-)passive investment strategy (which Multi-Factor-Investing or Smart-Beta Investing is perfect for) that considers a one-time investment and a monthly savings plan. Considering the wide investment-horizon we have a rather high risk tolerance but since we plan on investing monthly we want a steady performance.
- Which markets should we cover? The best yet simplest way to gain a large diversification while containing a good overview is a conservative DM (Developed Markets)/EM (Emerging Markets) strategy. For the allocation between theese we use the results of a Morgan Stanley study that states the optimized allocation bewtween an EM vs DM portfolio (Method: Max Risk/Return) since 1988 (which is close to the start date of the DM data we use) lies at 27% for EM [1].
- Therefore we seperately must A) Find the best Factors to use for DM/EM based on MSCI and other studies B) Consider the investability for private Investors via ETFs (for which factors are ETFs available, whats their TER, MC ...) and C) find the best optimization method between the Facotrs for Backtesting and Monte-Carlo simulations with and without constraints (HRP, Risk-Parity, Max Sharpe, Min Volatility, allocation based on factor-correlation (minimum correlation)...)  and lastly D) compute/ optimize the Allocations.





[1] Morgan Stanley: https://www.morganstanley.com/im/publication/insights/articles/article_howmuchtoown_us.pdf

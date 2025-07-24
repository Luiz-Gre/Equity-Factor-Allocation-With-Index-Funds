# Equity-Factor-Allocation-With-Index-Funds
The goal of this project was to find an optimal but simple allocation to various factor indexes in the equity market for personal investment goals.

The ideas of the project in logical order:

- What is our investment-goal? The ivestment-horizon is set between 25 to 30 years. We want a (semi-)passive investment strategy (which Multi-Factor-Investing or Smart-Beta Investing is perfect for) that considers a one-time investment and a monthly savings plan. Considering the wide investment-horizon we have a rather high risk tolerance but since we plan on investing monthly we also want a steady performance.
  
- Which markets should we cover? The best yet simplest way to gain a large diversification while containing a good overview is a conservative DM (Developed Markets)and EM (Emerging Markets) strategy. For the allocation between those we use the results of a Morgan Stanley study that states the optimized allocation bewtween an EM vs DM portfolio (Method: Max Risk/Return) since 1988 (which is close to the start date of the DM data we use) lies at 27% for EM [1].
  
- Therefore we must seperately
  A) find the best Factors to use for DM/EM based on MSCI and other studies
  B) consider the investability for private investors via ETFs (for which factors are ETFs available, whats their TER (Total Expense Ratio), MC (Market Capitalization) ...) and
  C) find the best optimization method between the Facotrs for Backtesting and Monte-Carlo simulations with and without constraints (HRP, Risk-Parity, Max Sharpe, Min Volatility, allocation based on factor-correlation (minimum correlation method)...)  and lastly
  D) compute/optimize the Allocations.

A) For DM: Based on [2] 




[1] Morgan Stanley: https://www.morganstanley.com/im/publication/insights/articles/article_howmuchtoown_us.pdf
[2] Fama/Fench (1993): https://www.bauer.uh.edu/rsusmel/phd/Fama-French_JFE93.pdf
[3] Fama/Fench (2015): https://www.sciencedirect.com/science/article/abs/pii/S0304405X14002323
[4] Jegadeesh/Titman (1993): https://www.bauer.uh.edu/rsusmel/phd/jegadeesh-titman93.pdf
[5] Carhart (1997): https://econpapers.repec.org/article/blajfinan/v_3a52_3ay_3a1997_3ai_3a1_3ap_3a57-82.htm
[6] MSCI (Market Data): https://www-cdn.msci.com/web/msci/index-tools/end-of-day-index-data-search
[7] 

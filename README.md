# sp500

## Regression Analysis on S&amp;P 500 Index Return

### ABSTRACT

Under the law of one price, index prices are expected to exhibit a mean-reverting nature. In other words, shocks to the equity market should be temporary and the mean of the asset’s price is to remain stationary over time. The historical or lagged return therefore can be interpreted as the support and resistance of the price fundamental.

As the Fed continues to combat inflation this year, we observed a notable shift in the equity investment landscape. By June 2022, the S&P 500 index slipped into a bear market as higher interest rates incentivized investors to sell assets and take profits. In an efficient market, fair asset prices can be interpreted as future discounted valuations and interest rates should have a negative relationship with securities return.

Based on the Gordon Growth Model, Cutler, Poterba, and Summers (1991) [1] study employed dividend yield, the inverse of the price-dividend ratio, as a statistically significant predictive power for international equity return, particularly in the United States where the volatility of real dividend growth is low. JP Morgan Research (2014) [2] further revealed that, for every one percent increase in dividend yield, market prices rise by approximately five percentage points.

In this project, we extracted monthly S&P index price data from Yahoo Finance, spot interest rate from FRED, and price-dividend ratio from Shiller’s website.

### FINDINGS

This project is an attempt to empirically investigate the effect of (1) Lagged Return, (2) Interest Rates, and (3) Price Dividend Ratio on the S&P 500 index return using the Linear Regression model. While the model created in this study might not be the best fit for the data, we need to remember that the returns on the S&P 500 are influenced by various macro and micro economic conditions such as natural calamities, political upheaval, exchange rate fluctuations, etc, which cannot be fully captured by only three explanatory variables. In traditional asset pricing, the Fama French three/five-factor model improved CAPM by constructing additional factors to describe stock returns. For future work, we propose adding sector-specific metrics and polynomial attributes to better predict variation in the sector-wide return in the S&P index.

### REFERENCES

[1] Cornell, B. (2014). Dividend-price ratios and stock returns: international evidence. The Journal of Portfolio Management, 40(2), 122–127. https://doi.org/10.3905/jpm.2014.40.2.122

[2] Cutler, David M., et al. “Speculative Dynamics.” The Review of Economic Studies, vol. 58, no. 3, 1991, pp. 529–46. JSTOR, https://doi.org/10.2307/2298010. Accessed 11 Oct. 2022.

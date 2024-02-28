# Portfolio-Optimization


----------------------------------- OBJECTIVE AND OVERVIEW

This is my first independent analysis involving OHLC stock price data.

Our goal is to: 
1) Gain insight on stock performance over time by analyzing close price data, and
2) Create an optimal portfolio containing these stocks.

In this analysis, we explore historical Adjusted Close stock price data pertaining to five of the most prestigious financial instituions to gain insight on their performance over time. Then, we create an equally-weighted portfolio containing these stocks, use the Efficient Frontier method to derive a large set of portfolios with randomly-generated, unequal weights, and find which portfolio is optimal by calculating and comparing their Sharpe Ratios. Finally, we compare these Sharpe Ratios with those of each individual institution, arriving at the best possible solution for investing in these stocks. This project aims to provide insights into portfolio construction and risk-return optimization strategies for investors.

The data analyzed in this project is fetched from Yahoo Finance.

----------------------------------- KEY CONCEPTS / TERMINOLOGY


* **OHLC Data** - OHLC stands for "Open, Close, Low, Close" and refers to stock prices on a given day.
  
  - The **Open** price is the first price a stock was listed for on a specified date.
  - The **High** price is the highest sale price the stock was listed for on that day.
  - The **Low** price is the lowest sale price the stock was listed for on the same day.
  - The **Close** price refers to the last price that the stock was listed for on that day.

    The full OHLC data set contains two additional columns:

    - **Adjusted Close** prices differ from Close prices. While Close prices are simply the closing price of a stock on a given day, Adjusted Close prices take corporateactions into account (e.g. stock splits, dividens, and more) that affect the stock's true performance. Thus, using Adjusted Close prices in financial analyses is more accurate.
    - **Volume** refers to the number of trades that occurred on the specified date.

  
* **Return / Cumulative Return** - Returns refer to the change in close or adjusted close prices, represented as a percentage. Cumulative returns are the aggregation of all returns prior to a specified date.


* **Portfolio Expected Return** - This is a key metric of portfolio analysis and is a measure of how much we can expect in return for investing in portfolio stocks. This is calculated by multiplying the historical mean of the asset returns with the weight of the assets. 


* **Portfolio Risk / Portfolio Standard Deviation** - Risk, which is measured by the standard deviation of returns, is the second key metric in portfolio analysis. This gives us the level of uncertainty in how much return we can expect from a portfolio.


* **Efficient Frontier** - The Efficient Frontier is a concept that delivers a set of optimal portfolios with various expected returns, risk levels and asset weights. This allows us to find the highest expected return at each level of risk and automatically presents us with the asset weights needed to achieve this portfolio.


* **Sharpe Ratio / Maximum Sharpe Ratio** - This is a measure used to evaluate return given a specified level of risk. It is equal to the return divided by the ratio. A higher Sharpe Ratio indicates better risk-adjusted performance.
  



----------------------------------- METHODOLOGY



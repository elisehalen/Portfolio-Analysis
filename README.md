# Portfolio-Analysis
Creating an equally-weighted portfolio, finding an optimal portfolio by adjusting weights and comparing their sharpe ratios with those of individual stocks to find optimal solution.


----------------------------------- OBJECTIVE AND OVERVIEW

This is my first independent analysis involving Adjusted Close stock prices.

Our goal is to: 
1) Gain insight on stock performance over time by analyzing close price data, and
2) Create different portfolio options containing these stocks and uncover which portfolio is optimal.

In this analysis, we explore historical Adjusted Close stock price data pertaining to five of the most prestigious financial instituions to gain insight on their performance over time. Then, we create an equally-weighted portfolio containing these stocks, use the Efficient Frontier concept to derive a large set of portfolios with randomly-generated, unequal weights, and find which portfolio is optimal by calculating and comparing their Sharpe Ratios. Finally, we compare these Sharpe Ratios with those of each individual institution, arriving at the best possible solution for investing in these stocks.


----------------------------------- KEY CONCEPTS / TERMINOLOGY


* **OHLC Data** - OHLC stands for "Open, Close, Low, Close" and refers to stock prices on a given day.
  
  ** The Open price is the first price a stock was listed for on a specified date.
  ** The High price is the highest sale price the stock was listed for on that day.
  ** The Low price is the lowest sale price the stock was listed for on the same day.
  ** The Close price refers to the last price that the stock was listed for on that day.

The full OHLC data set contains two additional columns:

** Adjusted Close prices differ from Close prices. While Close prices are simply the closing price of a stock on a given day, Adjusted Close prices take corporate actions into account (e.g. stock splits, dividens, and more) that affect the stock's true performance. Thus, using Adjusted Close prices in financial analyses is more accurate.

** Volume refers to the number of trades that occurred on the specified date.

The data fetched for this analysis comes from Yahoo Finance.

  
* **Return / Cumulative Return** - Returns refer to the change in close or adjusted close prices, represented as a percentage. Cumulative returns are the aggregation of all returns prior to a specified date.

  
* **Portfolio Expected Return** - This is a key metric of portfolio analysis and is a measure of how much we can expect in return for investing in portfolio stocks. This is calculated by multiplying the historical mean of the asset returns with the weight of the assets. 

* **Portfolio Risk / Portfolio Standard Deviation** - Risk, which is measured by the standard deviation of returns, is the second key metric in portfolio analysis. This gives us the level of uncertainty in how much return we can expect from a portfolio.


* **Efficient Frontier** - The Efficient Frontier is a 
* **Sharpe Ratio / Maximum Sharpe Ratio**
  



----------------------------------- METHODOLOGY

Then, we calculate returns, cumulative returns, and visualize monthly cumulative returns to get a clear idea as to how these financial institutions have performed over time. 

Next, we create an equally-weighted portfolio containing these stocks and analyze its expected return and risk

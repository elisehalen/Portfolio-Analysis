# Portfolio-Analysis
Creating an equally-weighted portfolio, finding an optimal portfolio by adjusting weights and comparing their sharpe ratios with those of individual stocks..


----------------------------------- OBJECTIVE AND OVERVIEW

This is my first independent analysis involving Adjusted Close stock prices.

Our goal is to: 
1) Gain insight on stock performance over time by analyzing close price data, and
2) Create different portfolio options containing these stocks and uncover which portfolio is optimal.

In this analysis, we explore historical Adjusted Close stock price data pertaining to five of the most prestigious financial instituions to gain insight on their performance over time. Then, we create an equally-weighted portfolio containing these stocks, use the Efficient Frontier concept to derive a large set of portfolios with randomly-generated, unequal weights, and find which portfolio is optimal by calculating and comparing their Sharpe Ratios. Finally, we compare these Sharpe Ratios with those of each individual institution, arriving at the best possible solution for investing in these stocks.


----------------------------------- KEY CONCEPTS / TERMINOLOGY


* OHLC Data - OHLC stands for "Open, Close, Low, Close" and refers to stock prices on a given day.
  
  ** The Open price is the first price a stock was listed for on a specified date.
  ** The High price is the highest sale price the stock was listed for on that day.
  ** The Low price is the lowest sale price the stock was listed for on the same day.
  ** The Close price refers to the last price that the stock was listed for on that day.

The full OHLC data set contains two additional columns:

** Adjusted Close prices differ from Close prices. While Close prices are simply the closing price of a stock on a given day, Adjusted Close prices take corporate actions into account (e.g. stock splits, dividens, and more) that affect the stock's true performance. Thus, using Adjusted Close prices in financial analyses is more accurate.

** Volume refers to the number of trades that occurred on the specified date.

The data fetched for this analysis comes from Yahoo Finance.

  
* Adjusted Close Price
* Return / Cumulative Return
* Portfolio Expected Return
* Portfolio Risk / Portfolio Standard Deviation
* Efficient Frontier
* Sharpe Ratio / Maximum Sharpe Ratio
* 



----------------------------------- METHODOLOGY

Then, we calculate returns, cumulative returns, and visualize monthly cumulative returns to get a clear idea as to how these financial institutions have performed over time. 

Next, we create an equally-weighted portfolio containing these stocks and analyze its expected return and risk

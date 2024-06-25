# Bank Stock Analysis

## Overview

The primary objectives of this analysis are:
- To understand the price changes over time for each bank stock.
- To calculate and interpret the average daily returns.
- To compute moving averages for better trend analysis.
- To determine correlations between closing prices and daily returns of different bank stocks.
- To evaluate the investment risk associated with each bank stock.
- To visualize the relationships and distributions of stock data.

## Data Sources

The historical stock data was fetched using Yahoo Finance.

## Key Questions Explored

1. **How has the price of bank stocks changed over time?**
   - Visualized the historical closing prices of each bank stock.

2. **What is the average daily return of bank stocks?**
   - Calculated daily returns and plotted their distributions.

3. **What are the moving averages of various bank stocks?**
   - Computed moving averages to identify trends over different periods.

4. **What is the correlation between closing prices of different bank stocks?**
   - Analyzed pairwise correlations using scatter plots and correlation matrices.

5. **What is the correlation between daily returns of different bank stocks?**
   - Visualized the correlations to understand how returns move in relation to each other.

6. **How much investment risk is associated with specific bank stocks?**
   - Assessed the risk by analyzing the standard deviation of daily returns.

7. **How can we predict the future behavior of bank stocks?**
   - Used historical trends and correlations to make informed predictions.

## Analysis Steps

1. **Data Retrieval**
   - Fetched historical stock data for HDFC, ICICI, SBI, Axis, and Kotak banks from Yahoo Finance.

2. **Data Cleaning**
   - Handled missing values and ensured data consistency.

3. **Descriptive Statistics**
   - Used `describe()` to get summary statistics (mean, std, min, max, percentiles) for each stock.

4. **Daily Return Calculation**
   - Computed daily returns to understand day-to-day changes.

5. **Visualization**
   - Plotted closing prices, daily returns, and distributions.
   - Used pair plots and joint plots for correlation analysis.

6. **Risk Analysis**
   - Analyzed the volatility of stocks by looking at the standard deviation of daily returns.

## Visualizations

- **Closing Prices Over Time**: Line charts showing how each stock's closing price has evolved.
- **Daily Returns**: Histograms and KDE plots illustrating the distribution of daily returns.
- **Correlation Analysis**: Pair plots and joint plots to visualize relationships between different stocks' returns.
- **Volume Traded**: Bar charts showing the trading volume over time.

## Conclusion

This analysis provides a comprehensive overview of the historical performance and risk assessment of major banking stocks in India. The visualizations and statistical summaries help in understanding the behavior of these stocks, aiding in better investment decisions.



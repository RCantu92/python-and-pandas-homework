# Quantitative Analysis with Python and Pandas

This project aims to help determine which portfolio is performing the best across many areas: volatility, returns, risk, and Sharpe ratios.

It does so by creating a tool (an analysis notebook) that analyzes and visualizes the major metrics of the portfolios across all of the aforementioned areas, and determine which portfolio outperformed the others. You will be given the historical daily returns of several portfolios: some from the firm's algorithmic portfolios, some that represent the portfolios of famous "whale" investors like Warren Buffett, and some from big hedge and mutual funds.  You will then use this analysis to create a custom portfolio of stocks and compare its performance to that of the other portfolios, as well as the larger market (S&P 500).

## Getting Started

### Prepare the Data

First, CSV files were read and cleaned several for analysis. The CSV files include whale portfolio returns, algorithmic trading portfolio returns, and S&P 500 historic prices.

### Conduct Quantitative Analysis

The data was then analyzed to see if any of the portfolios outperform the stock market (i.e., the S&P 500).

#### Performance Analysis

1. Calculated and ploted cumulative returns.

2. Calculated the cumulative terms by month and year.

#### Risk Analysis

1. Created a box plot for each of the returns.

2. Calculated the standard deviation for each portfolio.

#### Rolling Statistics

1. Ploted the rolling standard deviation of the firm's portfolios along with the rolling standard deviation of the S&P 500.

2. Constructed a correlation table for the algorithmic, whale, and S&P 500 returns.

3. Chose one portfolio and ploted a rolling beta between that portfolio's returns and S&P 500 returns.

### Plot Sharpe Ratios

Investment managers and their institutional investors look at the return-to-risk ratio, not just the returns. Knowing this, Sharpe Ratios were calculated.

1. Using the daily returns, calculated and visualized the Sharpe Ratios using a bar plot.

2. Determined whether the algorithmic strategies outperformed both the market (S&P 500) and the whales portfolios.

### Create Custom Portfolio

Now chose own portfolio that performed just as well as the algorithmic portfolios. Investigated by doing the following:

1. Visited NASDAQ's Historical Price Data and chose 3-5 stocks for own portfolio.

2. Downloaded the data as CSV files and calculated the portfolio returns.

3. Added own portfolio returns to the DataFrame with the other portfolios and reran the analysis.

## Built With

* [Python](https://www.python.org/) - Programming language.
* [Pandas](https://pandas.pydata.org/) - Data analysis and manipulation tool.

## Authors

* **Roberto Cantu**  - [GitHub](https://github.com/RCantu92)
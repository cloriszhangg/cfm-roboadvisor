# cfm-roboadvisor

## Introduction
Our team chose to build a safe portfolio, which means we wanted the total portfolio value to experience very minimal change from the starting value of 500,000 dollars between the start date and the end date. Since the maximum number of stocks we are allowed to include in our portfolio is 25, we chose to have the maximum number of stocks allowed in our portfolio. This was because we want to have our portfolio as diversified as possible, in order to mitigate non-systematic risk such as business risk, financial risk and default risk. Through diversification, investors are able to reduce the non-market risk, but they are unable to reduce the systematic risk. This means having an inter-industry portfolio with the least correlated stocks from different industries. This is to neutralize the negative performance of an individual stock on the total portfolio value. Additionally, by having a diversified portfolio, the effect of business risk within one industry is minimized by the better performing investments in other industries. For instance, stricter policies or higher taxes on businesses within the financial industry, would not affect companies in the healthcare industry as there is no correlation between the two. 

However, if the csv file provided contains less than 25 tickers, then we will include all of them in our portfolio and decide the weightings based on our correlation calculations that are discussed further in step 6. In order to generate the safest portfolio, we took historical data from November 1st, 2018 to November 24th, 2022. We chose a starting date before COVID-19 to gain an accurate representation of the overall trend of each stock as during 2020, as almost all stocks in different industries experienced large fluctuations.  Through various measures of portfolio risk, we were able to generate a portfolio with the maximum number of stocks and their optimal weightings.  

## Our Strategy
In order to pick 25 stocks to build our safe portfolio, we want to be able to quantify and measure the risk of our total portfolio to ensure it is as safe as possible. The three measures we used are beta, which is a measurement of systematic risk, standard deviation, which is a measurement of the total risk of our portfolio’s expected return, and correlation, which is a measurement of how closely the returns of each security are related to each other. 

The following is a summary of the strategy we implemented: 
1. Filter the Stocks
2. Calculate Beta
3. Calculate Standard Deviation
4. Rankings
5. Calculate Correlation
6. Portfolio Weightings
7. Generate Final Portfolio

Each step of our strategy explains more in depth on how each measure is used to create a safe portfolio.

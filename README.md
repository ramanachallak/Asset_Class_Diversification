# Asset_Class_Diversification

# Introduction

An asset class analysis between stocks and cryptocurrencies. We use data analysis to determine if market is in a good state to make a trade and then use signal analysis to determine long/short bias. Strategies are built using stocks and cryptos and compared to the overall performance of the S&P 500. The first strategy is a portfolio of stocks. Also we compare a strategy of a portfolio of cryptos.

# Clean the data:
APIs used:
Alpaca
Quandl

# Should we trade?

First, we need to determine when its a good time to trade. We read the data on an hourly basis and evaluate using Volume, Volatility and price change. 

Volume:
here we put volume acceptability stats and selected time frame

Visualization: volume stats over test period


Volatility/Price change:
here we put volume acceptability stats and selected time frame

Visualization: price change stats over test period

# What trades should we make?
Trade acceptance and bias is based on EMA and RSI analysis

EMA: EMA is the exponential Moving Average and is used to measure momentum in the market. Trade bias is long when price is higher than 200 period exponential moving average and short when below it. We use blank* to read and evaluate EMA.

Visualization: EMA over test period

RSI: RSI is the Relative Strength Index. It is measured by values 0-100. When the reading is below 30 it is determined to be oversold and is a buy trigger. When the value is over 70 it is considered overbought and is a sell signal. We use blank* to read and evaluate RSI.

Visualization: RSI over test period

# Comparing the strategies

Portfolios are compared for the last 30 days. We determined that blank* was the best strategy and blank* did blank*

Visualization of portfolios vs. SPY



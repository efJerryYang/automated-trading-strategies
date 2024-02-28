# Automated Trading Strategies

This repository would mainly record my understanding towards automated trading.

## Feature Engineering

As far as I know, there are two main topics in automated trading:

1. Perform predictions on very a large collection of stocks (over 1000 possibly), and do long/short directly. (alpha-based forecasting by WorldQuant BRAIN)
2. Maintain a portfolio of limited stocks, keep adjusting the partitions and choosing&removing stocks. (portfolio-based, mostly for individual investors)

This two topics are just simple ideas directly from my mind. I heard of a lot of "alphas" in many platforms, and also "factors" as well, but I cannot tell if they are the same thing.

But basically, they represent a shared idea: find the most representive "features" to help the investors understand the market and the conditions of the stocks. So I think the "feature engineering" part is always needed, whatever the methods one used to do the feature engineering.

There are some pretty good repositories that I found that may be helpful in doing the feature engineering especially for tradings, and we should also bear in mind that, those features are actually mathematical formulas (let's say, the alpha101), and therefore we can use methods related to program synthesis.

## Backtesting

Very good frameworks for automated trading:

1. [AutoTrader](https://github.com/kieran-mackle/AutoTrader)
2. [Intelligent Trading Bot](https://github.com/asavinov/intelligent-trading-bot)

## Papers

Before getting started, I should read some papers to understand what the current algorithmic trading is like.

Keywords to search on Google Scholar:

1. "trading reinforcement learning"
2. "algorithmic trading"
3. "trading strategies"

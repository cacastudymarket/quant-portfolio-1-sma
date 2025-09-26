# SMA Crossover Backtest on Bitcoin

## Dataset
- Source: [Kaggle Cryptocurrency Historical Data](https://www.kaggle.com/datasets/sudalairajkumar/cryptocurrencypricehistory)
- File: `coin_Bitcoin.csv`
  
## Method
- SMA50 vs SMA200 crossover
- Buy signal: SMA50 > SMA200
- Sell signal: SMA50 < SMA200
  
## Results
- Sharpe Ratio: 0.51
- Max Drawdown: -95.7%
- Strategy works better in sideways/bear market, but weak in strong bull market.

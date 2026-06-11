# Bitcoin Sentiment vs Trader Performance

analyzed hyperliquid trading data against the bitcoin fear & greed index
to see if market sentiment actually affects how traders perform. spoiler — it does.

## what's in here
- fear_greed_index.csv — daily bitcoin sentiment scores
- historical_data.csv — 211k+ trades from hyperliquid
- notebook.ipynb — all the analysis and charts

## what i found
- fear zones generate more PnL per trade than greed zones
- shorts print during fear, longs print during greed
- HYPE and SOL outperformed BTC/ETH in total PnL
- sentiment is a legitimate trading edge if you actually use it

## stack
Python, Pandas, Matplotlib, Seaborn, Google Colab

## how to run
open the notebook in google colab, upload the two csv files, run all cells in order

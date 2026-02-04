# Trader Performance vs Market Sentiment Analysis  
**Primetrade.ai – Internship Assignment (Round 0)**

## Overview
This project explores how market sentiment, measured using the Crypto Fear & Greed Index, relates to trader behavior and performance on the Hyperliquid platform.  
The goal is to identify measurable differences in profitability, risk, and trading behavior across different sentiment regimes.

## Repository Contents
- `fear_greed_index.csv` – Daily market sentiment (Fear / Greed)
- `historical_data.csv` – Hyperliquid trader execution data
- `trader_sentiment_analysis.ipynb` – Main analysis notebook
- `README.md` – Project overview and instructions

## Environment & Dependencies
The analysis is implemented in Python using commonly used data science libraries:
- pandas
- numpy
- matplotlib
- seaborn

Install dependencies using:
```bash
pip install pandas numpy matplotlib seaborn
## Data Availability
The datasets used in this analysis exceed GitHub’s file size limit.

They can be downloaded from the original sources provided in the assignment:

- Fear & Greed Index:
  https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view

- Hyperliquid Trader Data:
  https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view

After downloading, place both CSV files in the same directory as the notebook before running.

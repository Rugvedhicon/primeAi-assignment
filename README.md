# Trader Performance vs Market Sentiment Analysis
**Primetrade.ai Internship Assignment (Round-0)**

## Project Overview
This analysis investigates the relationship between market sentiment (Crypto Fear & Greed Index) and trader performance on the Hyperliquid platform. The study focuses on performance deltas, behavioral shifts, and directional biases across varying sentiment regimes.

## Repository Structure
- `fear_greed_index.csv`: Daily market sentiment data.
- `historical_data.csv`: Hyperliquid trader execution history.
- `trader_sentiment_analysis.ipynb`: Primary analysis notebook.
- `README.md`: Project documentation.

## Setup & Requirements
The analysis is implemented in Python using the following libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

To install dependencies:
```bash
pip install pandas numpy matplotlib seaborn
```

## How to Run
1. Place the CSV data files in the same directory as the notebook.
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `trader_sentiment_analysis.ipynb` and execute all cells.

## Key Outputs
- **Data Integrity Audit**: Validation of dataset dimensions and consistency.
- **Merge Validation**: Verification of temporal alignment between datasets.
- **Comparative Analysis**: Performance metrics across Fear and Greed regimes.
- **Trader Segmentation**: Performance profiling by activity and exposure levels.
- **Strategy Derivation**: Data-backed trading rules for different sentiment states.

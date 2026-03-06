# Trader Performance vs Market Sentiment Analysis

## Objective
This project analyzes how Bitcoin market sentiment (Fear vs Greed) influences trader behavior and performance on the Hyperliquid trading platform.

## Datasets
1. Bitcoin Market Sentiment Dataset
2. Hyperliquid Historical Trader Dataset

## Methodology
The analysis includes:
- Data cleaning and preprocessing
- Converting timestamps and aligning datasets by date
- Merging trader activity with sentiment data
- Feature engineering to compute:
  - Daily trader PnL
  - Win rate
  - Average trade size
  - Trade frequency
  - Long vs Short trade ratio
- Trader segmentation using K-Means clustering

## Insights
1. Trader profitability shows higher volatility during Fear periods.
2. Long and short trades are relatively balanced, indicating adaptive trading strategies.
3. Larger trade sizes result in greater profit variability.

## Strategy Recommendations
- Reduce leverage and position size during Fear market conditions.
- Use momentum-based strategies during Greed sentiment while maintaining risk control.

## How to Run
Open the notebook `internshalaAss.ipynb` in Google Colab or Jupyter Notebook and run all cells sequentially.

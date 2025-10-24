# Assingnment-Primetrade.ai

# 

import pandas as pd

import numpy as np

import matplotlib.pyplot as plt

import seaborn as sns


# Trader Behavior Analysis vs. Market Sentiment

This project is a data analysis assignment for the Junior Data Scientist – Trader Behavior Insights position.

The objective is to explore the relationship between trader performance (from Hyperliquid) and market sentiment (from the Bitcoin Fear & Greed Index) to uncover patterns and deliver insights for smarter trading strategies.

# Key Analyses & Insights
This project focuses on answering three primary questions:

1. Profitability vs. Sentiment
Question: How does average trader profitability (Closed PnL) vary with market sentiment? Are traders more profitable in "Fear" or "Greed"?

Analysis: Calculated the mean Closed PnL for each sentiment category.

Visualization: pnl_vs_sentiment.png (Bar chart)

2. Trading Volume vs. Sentiment
Question: Do traders trade in larger volumes during specific sentiment periods?

Analysis: Calculated the total sum of Size USD for each sentiment category.

Visualization: volume_vs_sentiment.png (Bar chart)

3. Trader Actions (Buy/Sell) vs. Sentiment
Question: What is the proportion of 'Buy' vs. 'Sell' actions during different sentiment periods? (e.g., Do traders "buy the dip" in "Extreme Fear"?)

Analysis: Created a normalized crosstab to find the percentage of 'Buy' vs. 'Sell' actions for each sentiment category.

Visualization: side_vs_sentiment.png (Stacked bar chart)

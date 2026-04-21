### Data-Science-Intern-project-1-

## Analyzing Trader Performance vs. Market Sentiment on Hyperliquid
# Project Overview
This project investigates how Bitcoin market sentiment (Fear & Greed Index) influences the profitability and behavior of traders on the Hyperliquid decentralized exchange. Using over 200,000 trade records and high-frequency sentiment data, we identify profitable regimes and segment users into behavioral archetypes.

# Key Findings
Sentiment Regimes: 'Extreme Greed' environments correlate with the highest average win rates (39%), suggesting a strong momentum-following bias in successful trades.
The Volatility Trap: 'Extreme Fear' periods show the lowest win rates (33%) but the highest trade frequency, indicating significant retail 'over-trading' during market stress.
Trader Archetypes: Using K-Means clustering, we identified three distinct groups:
Professional/Scalpers: High-frequency (750+ trades/day), high win rate (45%).
Institutional/Whales: Massive trade sizes with strategic low-frequency execution.
Retail/Casual: Lower efficiency and high sensitivity to market sentiment.

# Technical Implementation
Data Ingestion: Robust Unix/String timestamp conversion and multi-source data merging.
Feature Engineering: Calculation of Win Rates, PnL distributions, and Trade Sizes.
Machine Learning: K-Means clustering for behavioral segmentation.
Visualization: Detailed distribution analysis using Seaborn and Matplotlib.

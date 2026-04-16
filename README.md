# 📊 Trader Performance vs Market Sentiment

## 📌 Objective
Analyze how market sentiment (Fear/Greed) impacts trader behavior and performance using Hyperliquid trading data.

---

## ⚙️ Setup

```bash
pip install pandas numpy matplotlib seaborn

▶️ How to Run
Open notebook.ipynb
Run all cells sequentially
Outputs (charts + tables) will be generated


🧠 Methodology
Cleaned and preprocessed trade data
Aggregated data at daily trader level
Created key metrics:
Daily PnL
Win rate
Trade frequency
Average trade size (risk proxy)
Long/short ratio
Merged with sentiment dataset (aligned by date)
Performed:
Comparative analysis (Fear vs Greed)
Behavioral analysis
Segmentation (risk, frequency, consistency)


📊 Key Insights
Trading activity and risk-taking increase significantly during Greed periods.
Higher activity does not guarantee better performance; overtrading increases volatility.
High-risk traders achieve higher returns but with increased variability.
Consistent traders significantly outperform others across all market conditions.


💡 Strategy Recommendations
Control Risk in Greed: Avoid excessive trading and large positions during bullish markets.
Leverage Consistency in Fear: Maintain disciplined strategies in volatile conditions.
Optimize Trade Frequency: Avoid overtrading; focus on high-quality trades.

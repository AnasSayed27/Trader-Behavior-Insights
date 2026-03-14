# Trader Behavior vs. Market Sentiment Analysis
This project analyzes the relationship between Bitcoin Market Sentiment (Fear & Greed Index) and trader performance on the Hyperliquid platform.

## 🚀 How to Run
1. Clone the repo: `git clone <your-repo-link>`
2. Install dependencies: `pip install -r requirements.txt`
3. Open `notebooks/trader_analysis.ipynb` in Jupyter or VS Code.

## 📊 Methodology
- **Data Integration:** Merged 211k+ trade records with daily sentiment data using time-normalization and left-joins.
- **Metric Engineering:** Developed Win Rate percentages and Average PnL metrics to quantify performance across different market moods.

## 💡 Key Insights
- **Momentum Wins:** The data reveals that **Extreme Greed** is the most profitable phase, with a **46.5% Win Rate** and **$67.89 Avg PnL**.
- **The Fear Gap:** **Extreme Fear** shows the lowest efficiency (**37% Win Rate**), suggesting that retail traders struggle significantly during high-volatility capitulation events.
- **Size Paradox:** Traders use larger position sizes in "Fear" phases but achieve better results with smaller, more precise positions in "Greed" phases.

## 📈 Strategy Recommendations (Rules of Thumb)
1. **The Greed Rule:** Increase trade frequency during Extreme Greed to capture trend momentum.
2. **The Fear Rule:** Reduce position sizes and tighten stop-losses during Extreme Fear to protect capital.
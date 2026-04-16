#  Trader Behavior Analysis using Market Sentiment

##  Overview
This project analyzes trader behavior and performance under different market sentiment conditions (Fear vs Greed). The goal is to understand how sentiment affects profitability, risk, and trading decisions.

---

##  Dataset
- Trading dataset (trade-level data)
- Fear & Greed Index (daily sentiment data)

---

##  Methodology
- Converted timestamps and aligned data at daily level
- Created key metrics:
  - Daily PnL
  - Win rate
  - Trade frequency
  - Position size (proxy for leverage)
  - Long/short ratio
- Merged sentiment with trading data
- Performed:
  - Sentiment-based analysis
  - Trader segmentation
  - Predictive modeling

---

##  Key Findings
- Performance varies across sentiment regimes  
- Traders behave more aggressively during Fear  
- Frequent and consistent traders outperform others  
- Trading behavior is a stronger predictor than sentiment  

---

##  Strategy Recommendations
- Reduce position size during Extreme Fear  
- Maintain disciplined trading activity  
- Adjust long/short bias based on sentiment  

---

## Bonus: Predictive Model
A Random Forest model was used to predict daily profitability, achieving ~80% accuracy. Trade size and trade frequency were the most important features.

---

##  How to Run
```bash
pip install pandas numpy matplotlib  datetime scikit-learn
jupyter notebook

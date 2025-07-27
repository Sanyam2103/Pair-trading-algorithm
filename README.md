# 📈 Pair Trading Algorithm – Machine Learning Project

## 📌 Overview
This project implements a machine learning-based pair trading algorithm to identify stock pairs with strong historical correlation and generate long-short trading signals for profit.

---

## 💼 Problem Statement
Use statistical and ML techniques to:
- Identify tradable stock pairs
- Model their price relationship
- Generate profitable buy/sell signals based on spread deviation

---

## 🧠 Key Techniques Used
- **Data Preprocessing** using Pandas & NumPy
- **Cointegration Testing** with the Engle-Granger method
- **Z-score normalization** for spread-based signal generation
- **Backtesting Strategy** to simulate trades and assess profitability

---

## 🗂️ Project Structure
| File | Description |
|------|-------------|
| `pair_trading_algo.ipynb` | Jupyter Notebook containing the complete pair trading pipeline |
| `README.md` | Project overview and usage guide |

---

## 📦 Requirements
- Python 3.8+
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `statsmodels` (for cointegration)

Install with:
```bash
pip install pandas numpy matplotlib seaborn statsmodels
```

---

## 🚀 How to Run
1. Open the notebook `pair_trading_algo.ipynb`
2. Load the historical price data (sample provided or from Yahoo Finance)
3. Run the cells to:
   - Test for cointegration
   - Normalize spreads
   - Generate trading signals
   - Evaluate profit/loss

---

## 📊 Features
- Automated pair selection using cointegration tests
- Trading signal generation using Z-score thresholds
- Profitability metrics & PnL visualization
- Easy to modify thresholds and parameters

---

## 📬 Author
**Sanyam**  
For educational use only. Open to collaboration and improvements.

---

> 💡 Ideal for algorithmic trading enthusiasts and quantitative finance learners!

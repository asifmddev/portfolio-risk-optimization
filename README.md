📊 Dataset

* Source: Nifty 50 historical data (Kaggle / NSE)
* Time Period: 2016 – 2020
* Records: 60,000+ daily observations
* Features: OHLC prices, volume, daily returns

⸻

⚙️ Methodology

1. Data Cleaning & Preparation

* Filtered relevant time period (2016–2020)
* Handled missing values using forward fill
* Removed duplicates
* Calculated daily returns for each stock

⸻

2. Exploratory Data Analysis (EDA)

* Identified top-performing and underperforming stocks
* Analyzed sector-wise returns
* Studied distribution of daily returns
* Observed volatility patterns across stocks

⸻

3. Portfolio Construction

Built 3 portfolio strategies:

* Conservative → Low-risk, stable stocks
* Balanced → Mix of risk and return
* Aggressive → High-growth, higher volatility

Metrics used:

* Sharpe Ratio (risk-adjusted return)
* Beta (market sensitivity)
* Volatility (risk)
* Correlation matrix (diversification)

⸻

4. Optimization

* Generated 50 random portfolios
* Constructed Efficient Frontier
* Identified optimal portfolios based on Sharpe Ratio

⸻

5. Risk Analysis

* Calculated Value at Risk (VaR) at 95% confidence
* Evaluated downside risk for each portfolio

⸻

6. Backtesting

* Period: July 2020 – December 2020
* Initial Investment: ₹10,00,000
* Compared performance vs Nifty 50 benchmark

⸻

📈 Key Results

* Balanced Portfolio achieved best risk-adjusted returns (Sharpe ~0.81)
* Aggressive Portfolio delivered highest returns (~5.5%)
* 2 out of 3 portfolios outperformed Nifty benchmark
* Portfolio diversification reduced risk (avg correlation ~0.30)
* VaR ranged between ₹37K – ₹48K (monthly risk range)

⸻

📊 Dashboard

The Tableau dashboard provides a visual overview of:

* Portfolio performance comparison
* Risk vs Return trade-offs
* Stock-level insights

📌 File: Dashboard/Dashboard.png

⸻

🧰 Tools & Technologies

* Python (Pandas, NumPy)
* Matplotlib, Seaborn
* Tableau (Dashboard Visualization)
* Excel (Data Handling)

⸻

📌 Business Insights

* Balanced portfolios offer optimal trade-off between risk and return
* Sector diversification plays a key role in reducing volatility
* High returns do not always mean better performance (risk-adjusted metrics matter)
* Data-driven portfolio strategies can outperform benchmark indices

⸻

🚀 Future Improvements

* Include real-time market data
* Add transaction costs for realistic backtesting
* Expand to multi-asset portfolios (bonds, ETFs)
* Deploy as interactive web app

⸻

👤 Author

Mohammed Asif Ahmed
Business Analyst
📧 dev.mdasif@gmail.com

# S-P-500-Stock-Trends-Market-Performance-Sector-Analysis

## 👨‍💼 Project Owner
**PRAN WASNIK**
Data Analyst | Financial Data Analytics Enthusiast

## 🚀 Project Overview
This project presents a comprehensive financial data analysis of **S&P 500 stocks over a 5-year period**, focusing on:
* Long-term return analysis
* Sector-wise risk vs return comparison
* Correlation between major sectors
* Portfolio performance evaluation
The objective is to simulate a **real-world investment analytics workflow** used by financial analysts, portfolio managers, and investment firms.
The dataset used contains 5 years of historical stock price data for S&P 500 companies.

## 📊 Dataset Information
* Source: Kaggle (S&P 500 Historical Stock Data)
* File Used: `all_stocks_5yr.csv`
* Time Period: 5 Years
* Key Columns:
  * Date
  * Open
  * High
  * Low
  * Close
  * Volume
  * Stock Name
  
## 🎯 Business Objectives
This project answers the following investment-focused business questions:
1. Which S&P 500 companies delivered the highest total returns over 5 years?
2. How do risk (volatility) and return compare across sectors?
3. How correlated are major sectors like Technology, Financials, and Energy?
4. How does an equal-weight portfolio perform compared to a sector-weighted portfolio?

## 🛠 Tools & Technologies Used
* Python
* Pandas (Data Manipulation)
* NumPy (Numerical Computation)
* Matplotlib (Data Visualization)
* Seaborn (Statistical Visualization)
* Jupyter Notebook / Google Colab

## 📈 Analytical Workflow

### 1️⃣ Data Preprocessing
* Converted date column to datetime format
* Sorted data by stock and date
* Checked for missing values
* Calculated daily returns using percentage change

### 2️⃣ 5-Year Total Return Analysis
For each stock:
* Identified starting and ending price
* Calculated total return percentage
* Ranked companies by highest 5-year return
* Visualized Top 10 performing stocks
📌 Insight: Growth-oriented technology stocks tend to dominate long-term returns.

### 3️⃣ Risk vs Return (Sector-Level Analysis)
Mapped major stocks into sectors:
* Technology
* Financials
* Energy
For each sector:
* Calculated average daily return
* Calculated volatility (standard deviation)
* Compared risk-return tradeoff
📌 Insight:
* Technology sector shows higher returns with higher volatility.
* Financials provide moderate return with moderate risk.
* Energy sector exhibits cyclical behavior.

### 4️⃣ Sector Correlation Analysis
* Aggregated average sector prices
* Calculated sector-wise returns
* Generated correlation matrix
* Visualized heatmap
📌 Insight:
* Technology & Financials show moderate correlation.
* Energy sector often behaves differently due to macroeconomic and oil price influence.
* Correlation helps in diversification strategies.

### 5️⃣ Portfolio Performance Comparison
Two strategies evaluated:
🔹 Equal-Weight Portfolio
* Equal allocation to all stocks
🔹 Sector-Weighted Portfolio
* Technology: 40%
* Financials: 30%
* Energy: 30%
Compared cumulative growth over 5 years.
📌 Insight:
* Equal-weight portfolio provides diversified stability.
* Sector-weighted portfolio may outperform depending on sector dominance cycle.

## 📊 Key Metrics Calculated
* Daily Return
* 5-Year Total Return %
* Average Sector Return
* Volatility (Risk)
* Correlation Matrix
* Cumulative Portfolio Growth

## 📈 Business & Investment Impact
This analysis demonstrates:
* Performance benchmarking of S&P 500 stocks
* Sector diversification strategy evaluation
* Risk-return tradeoff assessment
* Portfolio allocation comparison
* Data-driven investment decision modeling
The workflow replicates how investment firms evaluate stock performance and sector allocation strategies.

## 📁 Project Structure
├── all_stocks_5yr.csv
├── s&p_500_stock_trends.py
├── README.md
└── Visualizations

## 🔮 Future Enhancements
* Sharpe Ratio Calculation
* CAPM Beta Analysis
* Rolling Volatility
* Monte Carlo Portfolio Simulation
* Efficient Frontier Optimization
* Machine Learning-based price prediction
* Real-time stock API integration

## 📌 Project Type
Individual Financial Data Analytics Project
Domain: Investment & Portfolio Analytics
Level: Company-Level Practice Simulation

## 📬 Contact
**PRAN WASNIK**
Data Analyst | Python | Financial Analytics
Open to opportunities in Data Analytics & Quantitative Finance

Tell me what you want next 🚀

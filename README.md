# Time Series Forecasting for Portfolio Management Optimization

## 10 Academy - Week 9 Challenge

### Overview
This project implements time series forecasting models to optimize portfolio management for GMF Investments. The solution includes:

- Data extraction from YFinance (TSLA, BND, SPY - 2015-2026)
- Exploratory Data Analysis and stationarity testing
- ARIMA and LSTM forecasting models
- Portfolio optimization using Modern Portfolio Theory
- Strategy backtesting against benchmark

### Project Structure
portfolio-optimization/
├── data/processed/ # Processed data files
├── notebooks/ # Jupyter notebooks for each task
├── src/ # Python source code
├── tests/ # Unit tests
├── scripts/ # Utility scripts
├── .github/workflows/ # CI/CD pipelines
├── requirements.txt # Python dependencies
└── README.md # Project documentation

### Setup Instructions
1. Clone the repository
2. Create virtual environment: `python -m venv venv`
3. Activate environment: `source venv/bin/activate` (Mac/Linux) or `venv\Scripts\activate` (Windows)
4. Install dependencies: `pip install -r requirements.txt`
5. Launch Jupyter: `jupyter notebook`

### Tasks Completed
- Task 1: Data Preprocessing and EDA
- Task 2: Time Series Forecasting Models
- Task 3: Future Market Trends Analysis
- Task 4: Portfolio Optimization
- Task 5: Strategy Backtesting

### Technologies Used
- Python 3.9+
- Pandas, NumPy
- Matplotlib, Seaborn
- YFinance
- Statsmodels, pmdarima
- TensorFlow/Keras
- PyPortfolioOpt
- Scikit-learn

### Author
Afyana Fekade
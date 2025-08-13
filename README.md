
# GMF Investment Portfolio Analysis

This project provides data analysis, forecasting, and backtesting for the GMF investment portfolio, focusing on time series modeling, portfolio optimization, and performance evaluation.

## Project Structure

- `data/` - Contains processed data files used for analysis.
- `models/` - Directory for saving trained models and related artifacts.
-- `notebooks/` - Jupyter notebooks for data exploration, model development, forecasting, portfolio optimization, and backtesting.
   - `data_exploration.ipynb` - Initial exploration and visualization of the dataset.
   - `model_development.ipynb` - Time series modeling and forecasting (e.g., ARIMA for TSLA stock).
   - `forcasting.ipynb` - Additional forecasting analysis and experiments.
   - `portfolio_optimization.ipynb` - Portfolio optimization techniques and results.
   - `backtesting.ipynb` - Backtesting of portfolio strategies and performance analysis.
- `src/` - Source code for custom scripts and utilities.
- `requirements.txt` - List of required Python packages.

## Getting Started

1. **Clone the repository**
2. **Install dependencies**
   ```powershell
   pip install -r requirements.txt
   ```
3. **Run the notebooks**
   - Open `notebooks/data_exploration.ipynb` for initial data analysis.
   - Open `notebooks/model_development.ipynb` for time series modeling and forecasting.
   - Open `notebooks/forcasting.ipynb` for additional forecasting analysis and experiments.
   - Open `notebooks/portfolio_optimization.ipynb` for portfolio optimization techniques and results.
   - Open `notebooks/backtesting.ipynb` for portfolio backtesting and performance evaluation.

## Main Features

- Data loading and preprocessing from CSV files
- Exploratory data analysis and visualization
- Time series forecasting using ARIMA models
- Portfolio optimization and strategy definition
- Backtesting of portfolio strategies against benchmarks
- Performance evaluation with metrics such as total return and Sharpe ratio

## Requirements

- Python 3.8+
- See `requirements.txt` for all dependencies

## License

This project is for educational and research purposes.

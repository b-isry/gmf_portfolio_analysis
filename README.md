# GMF Investment Portfolio Analysis

This project provides data analysis and forecasting for the GMF investment portfolio, focusing on time series modeling and exploratory data analysis of stock prices.

## Project Structure

- `data/` - Contains processed data files used for analysis.
- `models/` - Directory for saving trained models and related artifacts.
- `notebooks/` - Jupyter notebooks for data exploration and model development.
  - `data_exploration.ipynb` - Initial exploration and visualization of the dataset.
  - `model_development.ipynb` - Time series modeling and forecasting (e.g., ARIMA for TSLA stock).
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
   - Open `notebooks/model_development.ipynb` for time series modeling.

## Main Features

- Data loading and preprocessing from CSV files
- Exploratory data analysis and visualization
- Time series forecasting using ARIMA models
- Model evaluation with metrics such as MAE and MSE

## Requirements

- Python 3.8+
- See `requirements.txt` for all dependencies

## Troubleshooting

If you encounter errors related to `numpy` or `pmdarima` binary incompatibility, reinstall both packages:
```powershell
pip uninstall pmdarima -y; pip uninstall numpy -y; pip install numpy; pip install pmdarima
```

## License

This project is for educational and research purposes.

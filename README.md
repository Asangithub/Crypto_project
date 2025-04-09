
# Cryptocurrency Price Prediction with LSTM (2023–2025)

This project analyzes historical price trends and news sentiment to forecast cryptocurrency prices for 2025 using an LSTM model.
## Objective

-Collect historical price data for the top 10 cryptocurrencies (2023–2024)

-Gather crypto news headlines

-Perform data cleaning, exploratory data analysis (EDA), and sentiment analysis

-Train an LSTM neural network to predict 2025 prices

-Visualize results and export predictions

## Data Sources

- Price data from [Twelve Data API](https://twelvedata.com/)
- News data from [CryptoCompare News API](https://min-api.cryptocompare.com/data/v2/news/)

## Project Structure

- `crypto.ipynb` – main notebook with code and visualizations
- `*_historical_data.csv` – cleaned historical price datasets
- `crypto_prediction.zip` – full archive with notebook and CSVs

## Model

- Long Short-Term Memory (LSTM) neural network
- Trained on BTC/USD historical data
- Predicts closing prices for each day in 2025

## Results

- Sentiment analysis performed using TextBlob
- LSTM model predicts BTC/USD prices for 2025
- Visual plots included for analysis

## Requirements

```bash
pip install requests pandas matplotlib scikit-learn textblob tensorflow
```

## How to Run

1. Clone the repo or download the ZIP
2. Install dependencies
3. Run `crypto_price_prediction.ipynb` in Jupyter
4. View plots and predictions

## License

MIT License

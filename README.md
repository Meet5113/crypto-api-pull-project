# 📈 Crypto API Data Pull Using Python

This project pulls the latest cryptocurrency data from the CoinMarketCap API using Python in a Jupyter Notebook. The data is processed into a Pandas DataFrame, visualized, and exported to CSV.

## 🚀 Features

- Live API data pull using `requests`
- JSON to DataFrame conversion using `pandas.json_normalize`
- Error handling for failed requests
- Added timestamp for each data pull
- Data visualization with `matplotlib`
- Export to CSV (`crypto_data.csv`)

## 🛠️ Tools Used

- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib
- CoinMarketCap API

## 📊 Sample Visualizations

- Top 10 cryptocurrencies by market cap
- Price vs 24h Volume scatter plot

## 📁 Files

| File Name              | Description                          |
|------------------------|--------------------------------------|
| `crypto_data_pull.ipynb` | Main project notebook               |
| `crypto_data.csv`        | Output CSV with pulled data         |
| `README.md`              | Project overview and usage guide    |

## 📌 How to Use

1. Replace `'your_api_key_here'` with your actual CoinMarketCap API key in the notebook.
2. Run all cells.
3. View the visualizations and CSV output.


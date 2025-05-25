# Stock Market Prediction

This project uses machine learning models to predict stock prices for multiple companies using historical stock data, sentiment analysis from news headlines, and correlation analysis.

---

## Project Overview

- **Models used:**
  - Random Forest Regressor (RFR)
  - Long Short-Term Memory (LSTM) neural networks
  - Sentiment Analysis (SA) using NewsAPI and TextBlob

- **Data:**
  - Historical stock data over 5 years for multiple companies.
  - News headlines fetched for sentiment analysis.

- **Technologies:**
  - Python (Pandas, scikit-learn, TensorFlow/Keras, TextBlob)
  - Data visualization with Matplotlib and Seaborn
  - NewsAPI for news data

---

## Dataset

The dataset `all_stocks_5yr.csv` (~100+ MB) contains historical stock prices for multiple companies over 5 years.

**Due to GitHub file size limits, the dataset is hosted externally:**

[Download the dataset here](https://drive.google.com/file/d/1ZF1ui8uCsNfCQlu8nclkTlmptPZ_R7VU/view?usp=sharing)

---

## Files in this repository

- `rfr.ipynb` — Random Forest Regressor implementation and hyperparameter tuning
- `sentiment.ipynb` — Sentiment analysis of company news headlines
- `correlation_analysis.ipynb` — Correlation analysis comparing model predictions and actual prices
- Additional scripts and notebooks for data preprocessing, model training, and visualization

---

## How to run

1. Download the dataset from the link above and place `all_stocks_5yr.csv` in the project directory.
2. Install required packages:

```bash
pip install -r requirements.txt
Run the Jupyter notebooks in order, starting with data preprocessing and then model training.

Visualize results using provided notebooks.

API Keys
This project uses the NewsAPI for fetching news headlines.
You need to get your own API key and update the API key variable in the notebooks:

newsapi = NewsApiClient(api_key='YOUR_NEWSAPI_KEY')

License
This project is licensed under the MIT License.

Contact
Created by Chakri.
For questions or feedback, please open an issue or contact me at [chakrifavofvd@gmail.com].










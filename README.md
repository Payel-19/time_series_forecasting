# 📈 AAPL Stock Price Forecasting App

A **Time Series Forecasting Web Application** that predicts future stock prices using **ARIMA** and **LSTM (Deep Learning)** models, built with an interactive Streamlit dashboard.

---

##  Overview

This project provides a user-friendly web interface to forecast **Apple (AAPL) stock prices** using both:

*  **ARIMA (Statistical Model)**
*  **LSTM (Deep Learning Model)**

Users can visualize historical data, generate forecasts, and download prediction results.

---

##  Key Features

###  Real-Time Data

* Fetches historical stock data using `yfinance`
* Displays interactive time-series charts

###  Forecasting Models

* **ARIMA** → Traditional time series forecasting
* **LSTM** → Neural network-based prediction

###  Interactive UI

* Select forecast duration (5–120 days)
* Choose forecasting model (ARIMA / LSTM)
* Generate predictions dynamically

###  Visualization

* Interactive Plotly graphs
* Clear comparison of historical vs predicted data

###  Export Results

* Download forecast results as CSV file

---

##  Tech Stack

| Component     | Technology  |
| ------------- | ----------- |
| Frontend      | Streamlit   |
| Data Source   | yFinance    |
| ML Models     | ARIMA, LSTM |
| Deep Learning | TensorFlow  |
| Visualization | Plotly      |
| Model Storage | Joblib, H5  |

---

## Project Structure

```bash
.
├── app.py
├── app.ipynb
├── requirements.txt
├── README.md
├── models/
│   ├── arima_model_AAPL.joblib
│   ├── lstm_model_AAPL.h5

```

---

##  Installation

### 1️ Clone the Repository

```bash
git clone https://github.com/your-username/aapl-stock-forecast.git
cd aapl-stock-forecast
```

###  Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```

###  Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the App

```bash
streamlit run app.py
```

Open in browser:

```
http://localhost:8501
```

---

##  How It Works

1. Fetch historical AAPL stock data
2. Choose forecasting model:

   * ARIMA → statistical prediction
   * LSTM → deep learning prediction
3. Generate future price predictions
4. Visualize results and download data

---

##  Use Cases

* Financial data analysis
* Stock market prediction systems
* Time series forecasting projects
* ML/DL portfolio projects

---

##  Disclaimer

This project is for **educational purposes only**.
It should **not be used for real financial decisions or trading**.

---

##  Future Improvements

*  Add more stocks (multi-ticker support)
*  Add evaluation metrics (RMSE, MAE)
*  Improve LSTM architecture
*  Deploy on cloud (Streamlit Cloud / AWS)
*  Mobile-friendly UI



---

## ⭐ If you like this project

Give it a ⭐ on GitHub — it helps a lot!

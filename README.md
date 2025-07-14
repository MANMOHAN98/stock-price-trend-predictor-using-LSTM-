 Stock Price Trend Prediction with LSTM (Multi-Stock)

 Objective
Predict future stock prices for multiple symbols (AAPL, MSFT, TSLA) using LSTM.

 Tools Used
Python, Pandas, Keras, TensorFlow, Matplotlib, yfinance API, Streamlit

 Structure
- data/: Multiple stock CSVs
- notebooks/: stock_price_lstm.ipynb
- models/: Multiple .h5 model weights
- graphs/: Multiple prediction plots
- app.py: Streamlit dashboard with stock selector
- requirements.txt
- README.md

 How to Run
1. pip install -r requirements.txt
2. Run the notebook: train & save each stock’s model, generate graphs
3. streamlit run app.py


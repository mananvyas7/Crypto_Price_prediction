# Crypto_Price_prediction


🪙 Cryptocurrency Price Prediction using LSTM

📌 Description
This project aims to predict the future prices of cryptocurrencies (such as Bitcoin, Ethereum, or Litecoin) using Long Short-Term Memory (LSTM) neural networks, a powerful variant of recurrent neural networks (RNNs) well-suited for time series forecasting.
The model learns from historical price data (Open, High, Low, Close, Volume) and attempts to predict the next closing price based on trends and patterns.
🎯 Objectives
Collect historical cryptocurrency price data using yFinance API.
Preprocess the data for time series modeling.
Build and train an LSTM-based deep learning model for price forecasting.
Evaluate the model's performance using metrics like MSE, RMSE, and R² score.
Deploy the prediction system using a Flask or FastAPI backend for API access.
Optionally connect to a React frontend for user interaction.
🔧 Technologies Used
Python (for data processing and modeling)
Pandas, NumPy (for data manipulation)
TensorFlow / Keras (for building the LSTM model)
scikit-learn (for evaluation metrics and preprocessing)
yFinance (to fetch crypto price data)
Flask / FastAPI (for backend API)
React.js (optional, for frontend visualization)
📈 Workflow Overview
Data Collection → using yFinance API.
Preprocessing → Normalize, clean, and convert to supervised sequences.
Model Building → LSTM model to learn temporal price patterns.
Training & Evaluation → Split data, train model, validate predictions.
Prediction API → Expose endpoint for predicting next-day price.
Frontend (Optional) → Allow users to input date or range and get predicted prices.
📊 Example Use Cases
Predict next-day Bitcoin closing price.
Forecast weekly trends in Ethereum.
Visualize actual vs predicted prices.

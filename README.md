# Stock-price-predictor

This program implements two deep learning models—LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit)—to predict future stock prices based on historical stock price data.

The primary goal is to use time series data (such as open, high, low, close prices, and volume) to forecast future prices and compare the performance of LSTM and GRU models.

The program preprocesses the data by scaling it, reshapes it to fit the requirements of recurrent neural networks, trains the models on this data, and then evaluates the models using the R-squared regression metrics .

The program is divided into three key parts:
1. **Data Preprocessing** - Preprocess the Data according to the Model Requirements.
2. **Training the Models** – Trains the LSTM and GRU models on the stock price dataset.
3. **Predicting Stock Prices** – Uses the trained models to make predictions and evaluate their performance.

## Instructions to Run the Program

### Step 1: Clone the Repository
First, clone the repository to your local machine using Git:
  git clone https://github.com/nivedphil/Stock-price-predictor.git
  cd Stock-price-predictor

The Libraries required to run the models are: Pandas, NumPy, MatplotLib, Sci-kit Learn and TensorFlow

Open the Stock-price-predictor Folder in a Code Editor like Visual Studio Code, Jupyter Notebook or Google Colab etc any Editor that can support .ipynb files

To predict using LSTM Model, open LSTM_Stock_Price_predictor.ipynb and load the LSTM_stock_price_predictions.keras model and run the last two cells

To predict using GRU Model, open GRU_Stock_Price_prediction.ipynb and load the GRU_stock_price_predictions.keras model and run the last two cells

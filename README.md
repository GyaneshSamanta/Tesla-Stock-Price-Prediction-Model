# Tesla Stock Price Prediction Model 📈

🚀 **Predicting the future of Tesla stock using Deep Learning.**

This project implements a **LSTM (Long Short-Term Memory)** neural network to forecast Tesla's stock closing prices. LSTM is a type of Recurrent Neural Network (RNN) that is particularly effective for time-series forecasting due to its ability to remember long-term dependencies.

---

## 📂 Project Structure

The repository is organized as follows:

```text
Tesla-Stock-Price-Prediction-Model/
├── data/
│   └── tesla.csv             # Historical stock price dataset
├── notebooks/
│   └── tesla_stock_prediction.ipynb   # Main analysis & modeling notebook
└── README.md                 # Project documentation
```

---

## 🛠️ Technologies & Libraries

- **Python**: Core programming language.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computing.
- **Matplotlib**: For creating static, animated, and interactive visualizations.
- **Scikit-learn**: Used for data scaling with `MinMaxScaler`.
- **Keras & TensorFlow**: For building and training the LSTM model.
- **Pandas Datareader**: To fetch financial data.

---

## 🚀 Getting Started

### 1. Prerequisites

Ensure you have Python installed, along with the following libraries:

```bash
pip install numpy pandas matplotlib pandas_datareader scikit-learn tensorflow
```

### 2. Running the Analysis

1. Navigate to the `notebooks/` directory.
2. Open `tesla_stock_prediction.ipynb` in your preferred Jupyter environment (Jupyter Lab, VS Code, etc.).
3. Run the cells sequentially to visualize the data, preprocess it, train the model, and view the predictions.

---

## 📊 Dataset

The model uses historical Tesla stock data (OHLCV - Open, High, Low, Close, Volume). Specifically, the **Close** prices are used to predict future trends.

---

## 🧠 Model Architecture

- **Input Layer**: Takes sequences of past stock prices.
- **LSTM Layers**: Two or more LSTM layers to capture complex patterns in the time-series data.
- **Dense Layer**: Standard fully connected layer to output the predicted price.
- **Optimizer**: Adam optimizer is used for training.
- **Loss Function**: Mean Squared Error (MSE).

---

## 📈 Results

The model generates a visualization comparing the **Actual** prices against the **Predicted** prices, providing insights into its forecasting accuracy.

---

## 📝 License

This project is open-source. Feel free to contribute or modify it for your own analysis!

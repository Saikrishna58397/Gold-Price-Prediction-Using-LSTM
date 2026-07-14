# 🥇 Gold Price Prediction Using LSTM

## 📌 Overview

This project predicts future gold prices using a Long Short-Term Memory (LSTM) neural network. Historical gold price data is preprocessed, scaled, and used to train a deep learning model capable of learning temporal patterns in time-series data.

The project demonstrates practical applications of Deep Learning for financial forecasting using TensorFlow and Keras.

---

## 🚀 Features

- Gold price forecasting using LSTM
- Time-series data analysis
- Data preprocessing and cleaning
- Feature scaling using MinMaxScaler
- Interactive data visualization
- Deep learning model training
- Prediction of future gold prices
- Performance evaluation

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- LSTM
- Pandas
- NumPy
- Matplotlib
- Plotly
- Scikit-learn
- Google Colab

---

## 📂 Dataset

Historical Gold Price Dataset (2013–2023)

The dataset contains:

- Date
- Price
- Open
- High
- Low
- Volume
- Change %

---

## 🔄 Project Workflow

### 1. Import Libraries

- NumPy
- Pandas
- TensorFlow
- Keras
- Matplotlib
- Plotly
- Scikit-learn

---

### 2. Data Loading

- Load historical gold price dataset.
- Inspect dataset structure and statistics.

---

### 3. Data Preprocessing

- Remove unnecessary columns.
- Check missing values.
- Remove duplicates.
- Convert price values into numerical format.

---

### 4. Data Visualization

- Visualize historical gold price trends.
- Explore market movement using interactive charts.

---

### 5. Data Scaling

- Normalize data using MinMaxScaler.
- Prepare data for LSTM training.

---

### 6. Model Development

- Build an LSTM neural network using TensorFlow/Keras.
- Configure hidden layers and output layer.
- Compile the model using an appropriate optimizer and loss function.

---

### 7. Model Training

- Train the LSTM model on historical price sequences.
- Validate model performance using test data.

---

### 8. Model Evaluation

Performance is evaluated using:

- Mean Absolute Percentage Error (MAPE)
- Prediction Accuracy
- Visualization of Actual vs Predicted Prices

---

## 📊 Results

The trained LSTM model successfully learns historical trends and predicts future gold prices with good forecasting performance on unseen data.

---

## 📁 Project Structure

```
Gold-Price-Prediction-Using-LSTM
│
├── gold_price_prediction_lstm.ipynb
├── Gold Price (2013-2023).csv
├── README.md
├── .gitignore
└── requirements.txt
```

---

## 💡 Skills Demonstrated

- Deep Learning
- Time Series Forecasting
- LSTM Networks
- TensorFlow
- Keras
- Data Preprocessing
- Feature Scaling
- Data Visualization
- Financial Data Analysis
- Python Programming

---

## 🔮 Future Enhancements

- Predict prices multiple days ahead
- Deploy as a Streamlit web application
- Integrate live gold price data
- Compare LSTM with GRU and Transformer models


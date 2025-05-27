# 🌬️ Wind Energy Forecasting using Deep Learning

This project presents a deep learning-based approach for forecasting wind energy generation using historical wind data. We build and evaluate an LSTM (Long Short-Term Memory) neural network to predict future wind speeds and power output based on past patterns.

---

## 📌 Project Overview

Wind energy is a crucial component of sustainable power generation. However, due to its intermittent nature, forecasting wind power is essential for grid stability and energy planning.

This project aims to:
- Preprocess and visualize wind data.
- Engineer features and handle missing values.
- Train a time-series deep learning model (LSTM).
- Evaluate model performance and visualize results.

---

## 📊 Data Exploration

The dataset contains time-series wind speed measurements. Here's a quick look at the data and its characteristics.

### 📈 Wind Speed Over Time

![Wind Speed Graph](images/wind_speed_over_time.png)

*The graph shows fluctuations in wind speed over the recorded period.*

### 🔍 Correlation Heatmap

![Correlation Heatmap](images/correlation_heatmap.png)

*A heatmap to visualize the correlation between features, helping in feature selection.*

---

## 🧠 Model Architecture

We use a Recurrent Neural Network (RNN) with LSTM cells, which are ideal for time-series prediction tasks.

### Model Highlights:

- Scaled and reshaped data into time sequences.
- Used 80% for training and 20% for testing.
- LSTM layers followed by Dense output layer.
- Trained using Mean Squared Error (MSE) loss.

### 📉 Training Loss Curve

![Loss Curve](images/training_loss_curve.png)

*Loss function converges steadily over training epochs.*

---

## 🧪 Results

The model performs well in predicting short-term wind speed and power with minimal error.

### 📈 Predicted vs Actual Wind Speed

![Prediction vs Actual](images/predicted_vs_actual.png)

*The model captures the trend of actual wind speeds accurately.*

---

## 🗂️ Files Included

- `research_DL.ipynb`: Full Jupyter notebook with code, training, and evaluation.
- `Wind Data.csv`: The dataset containing historical wind measurements.
- `README.md`: This file.
- `requirements.txt`: Python package dependencies.

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/wind-energy-forecasting.git
cd wind-energy-forecasting

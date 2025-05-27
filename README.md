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

*The graph shows fluctuations in wind speed over the recorded period.*

### 🔍 Correlation Heatmap

(![Screenshot 2025-05-27 121410](https://github.com/user-attachments/assets/c67403c9-7274-49a0-afbc-3ac05df2007f)


*A heatmap to visualize the correlation between features, helping in feature selection.*

---

## 🧠 Model Architecture

We use a Recurrent Neural Network (RNN) with LSTM cells, which are ideal for time-series prediction tasks.

### Model Highlights:

- Scaled and reshaped data into time sequences.
- Used 80% for training and 20% for testing.
- LSTM layers followed by Dense output layer.
- Trained using Mean Squared Error (MSE) loss.

## 🧪 Results

The model performs well in predicting short-term wind speed and power with minimal error.

### 📈 Predicted vs Actual Wind Speed

![Screenshot 2025-05-27 120511](https://github.com/user-attachments/assets/14ffa8b2-9e26-4cf9-a85f-676c35556fcf)
![Screenshot 2025-05-27 120553](https://github.com/user-attachments/assets/353ef672-985f-4e23-a69e-18a938241b35)
![Screenshot 2025-05-27 120610](https://github.com/user-attachments/assets/1cd3865a-88ec-4711-8cff-d4df2344c65c)
![Screenshot 2025-05-27 120625](https://github.com/user-attachments/assets/8c85809f-2baa-429f-b7c1-b88749f49e75)





*The model captures the trend of actual wind speeds accurately.*

---

## 🗂️ Files Included

- `research_DL.ipynb`: Full Jupyter notebook with code, training, and evaluation.
- `Wind Data.csv`: The dataset containing historical wind measurements.
- `README.md`: This file.
- `requirements.txt`: Python package dependencies.

---

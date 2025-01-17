# 📈 StockCast-LSTM: Stock Price Prediction with LSTM



StockCast-LSTM is a **stock price prediction project** based on **Long Short-Term Memory (LSTM) networks**. The goal is to use historical stock prices to forecast future trends and evaluate model performance on a test set.  

---

## 🚀 Project Overview  

🔹 **Model Used**: LSTM (Long Short-Term Memory)  
🔹 **Data Used**: Amazon (AMZN) historical stock prices + technical indicators  
🔹 **Objective**: Predict stock closing prices based on past trends  
🔹 **Key Results**: RMSE **0.0357**, R² **0.8390**, and **96.92% accuracy** within a 10% margin of error  

---

## 📊 Visual Results  

### 🎯 Predictions on the Test Set  
![True vs Predicted](https://user-images.githubusercontent.com/example/predictions.png)  

📌 **Interpretation**:  
- The **blue line** represents the **real values**  
- The **dotted orange line** represents the **model’s predictions**  
- The model follows the general trend but may miss certain peaks  

### 🔍 Prediction Errors  
![Error Distribution](https://user-images.githubusercontent.com/example/error_distribution.png)  

📌 **Interpretation**:  
- Most errors are small and centered around **0**, indicating good generalization  
- Some larger errors still exist and could be reduced with further optimization  

---

## 🏗️ Model Architecture  

The model is based on an **LSTM network** with the following parameters:  

- **Input size**: Number of features used  
- **Hidden size**: 100 neurons  
- **Number of layers (num_layers)**: 2  
- **Dropout**: 0.2  
- **Optimizer**: Adam (learning rate = 0.002)  
- **Loss Function**: MSE (Mean Squared Error)  

📌 **Model Diagram**:  

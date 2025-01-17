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

📌 **Interpretation**:  
- The **blue line** represents the **real values**  
- The **dotted orange line** represents the **model’s predictions**  
- The model follows the general trend but may miss certain peaks  

### 🔍 Prediction Errors  

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

The **LSTM model architecture** used in this project is structured as follows:
(Input) -> [LSTM Layer] -> [LSTM Layer] -> [Fully Connected Layer] -> (Output)

## 📌 Performance Summary  

| **Metric**                     | **Value**    |
|--------------------------------|-------------|
| **Test Loss**                  | 0.0013      |
| **Test RMSE**                  | 0.0357      |
| **R² Score (Test)**            | 0.8390      |
| **% of correct predictions (±10%)** | 96.92%  |
| **% of correct trend predictions** | 51.09%  |
| **Sharpe Ratio**               | 0.06        |

📌 **Interpretation**: The model **predicts absolute values accurately** but struggles more with **trend direction accuracy**. Further optimizations may be required to improve trend detection.


---

## 📌 Possible Improvements  

🔹 **Feature Engineering**: Add more technical indicators such as Moving Averages, MACD, and RSI to improve trend detection.  
🔹 **External Data Integration**: Incorporate financial news, economic indicators, and market trends to provide broader context to price movements.  
🔹 **Hybrid Models**: Experiment with **LSTM + Transformer or Attention Mechanisms** to enhance long-term pattern recognition.  
🔹 **Hyperparameter Optimization**: Further fine-tune parameters, including testing different **time_step lengths** to optimize predictive accuracy.  

---

## 🤝 Contribute  

Contributions are welcome! Feel free to:  

- **🐛 Report a Bug** – Identify and document issues.  
- **💡 Suggest an Improvement** – Share ideas to optimize the model.  
- **🚀 Share Experiments** – Implement variations and compare results.  

---

## 📜 License  

This project is licensed under the **MIT License** – feel free to use, modify, and share it.  

---

## 📩 Contact  

📧 **Email**: yona.e@hotmail.fr  
🐙 **GitHub**: https://github.com/yona1997
🔗 **LinkedIn**: http://linkedin.com/in/yona-el-bar-082190223

---

🔥 **If you find this project useful, don't forget to ⭐ the repository!** 🔥  

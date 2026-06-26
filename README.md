# 📈 Stock Price Forecasting: LSTM vs N-BEATS

This project is a straightforward deep learning tool that compares two different AI models—**Bidirectional LSTM** and **N-BEATS**—to see which is better at predicting stock market prices. Everything runs directly inside Google Colab, meaning you do not need to worry about setting up complex servers, backends, or web pages.

---

## 🌟 What This Project Does

Given almost any stock symbol (like Apple, Tesla, or even crypto), this tool automatically handles the entire forecasting process from start to finish:

* **Fetches Data:** Downloads historical stock prices directly from the web.
* **Adds Context:** Calculates helpful trading indicators to understand trends, momentum, and volume.
* **Trains the AI:** Teaches two different models to predict future prices for 7, 14, or 30 days ahead.
* **Tests Performance:** Evaluates how accurate the predictions are, focusing heavily on whether the model correctly guessed if the price would go up or down.
* **Simulates Trading:** Runs a simulated trading strategy based on the AI's predictions to see how much money it would have made (or lost), factoring in transaction fees.
* **Declares a Winner:** Compares both models side-by-side with charts and automatically declares which AI performed better.

---

## 📁 How It Is Organized

The project is broken down into three easy-to-use Google Colab notebooks:

1.  **`stock_forecasting_LSTM.ipynb`:** Trains the LSTM model, a popular AI known for understanding patterns over time.
2.  **`stock_forecasting_NBeats.ipynb`:** Trains the N-BEATS model, a more specialized AI designed specifically for predicting time-based data.
3.  **`stock_forecasting_comparison.ipynb`:** Takes the saved results from the first two notebooks and pits them against each other without needing to retrain anything. 

---

## 🚀 How to Use It

All customizable settings (like the stock you want to predict or the dates you want to test) are kept in a single configuration block at the top of each notebook. 

To get started:
1.  Open the notebooks in Google Colab.
2.  Run the **LSTM notebook** from top to bottom.
3.  Run the **N-BEATS notebook** from top to bottom.
4.  Run the **Compare notebook** to generate the final charts, performance tables, and winner summary.

---

*Note: This project is for educational and research purposes only and does not constitute financial advice.*
# ⚡ Solar Panel Optimization using LSTM

This project predicts solar panel efficiency using an LSTM (Long Short-Term Memory) neural network. It processes environmental and operational data to build a time-series model for accurate efficiency estimation.

## 📄 Files

- `Code.ipynb`: Complete Jupyter Notebook with preprocessing, LSTM model training, evaluation, and result plots.
- `README.md`: Project overview.

## 🧰 Libraries Used

- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn (MinMaxScaler, train_test_split, metrics)
- TensorFlow (Keras Sequential + LSTM)

## 🚀 How to Use

1. Open `Code.ipynb` in Jupyter Notebook or VS Code
2. Run all cells top to bottom
3. The model will:
   - Scale the data
   - Train the LSTM model with early stopping
   - Evaluate performance (e.g., RMSE)
   - Plot predicted vs actual values

> All dependencies are directly imported inside the notebook.

## 📈 Model Summary

- Model: LSTM-based Regression
- Optimizer: Adam
- Loss Function: Mean Squared Error (MSE)
- Evaluation Metric: RMSE
- Result: ~89.88% Efficiency Score

## 👤 Author

**Vraj Patel**  
GitHub: [AshenWitch96](https://github.com/AshenWitch96)

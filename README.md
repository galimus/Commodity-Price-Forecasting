# Commodity Price Forecasting  

## Project Overview  
This project focuses on predicting **Commodity Research Bureau (CRB) Index** changes using machine learning. We applied **LSTM, XGBoost, and OLS** models for time series forecasting and compared their performance.  

## Key Files  
- **big_data.ipynb** – Jupyter Notebook for model training, and analysis.  
- **lstm_architecture.png** – Visualization of the LSTM model architecture.  
- **Enhanced_Processed_Financial_Data.csv** – Preprocessed financial dataset.
- **model_predictions.png** – Comparison of model predictions vs. actual CRB change. 
- **README.md** – This file with project details.  
- **Data_Processing.ipynb** - Jupyter Notebook for data processing.
## Methods & Technologies  
- **LSTM (Long Short-Term Memory)** – Capturing sequential dependencies in time series.  
- **XGBoost** – Gradient boosting for regression.  
- **OLS (Ordinary Least Squares)** – Linear regression as a baseline.  
- **Optuna** – Hyperparameter tuning for LSTM.  
- **Pandas, NumPy, Scikit-learn, TensorFlow, Matplotlib** – Libraries for data analysis and machine learning.  

## Results  
LSTM outperformed other models with:  
- **RMSE = 0.4842**  
- **R² = 0.6852**  

This confirms that neural network-based models better capture temporal dependencies and nonlinear patterns in financial time series data.  



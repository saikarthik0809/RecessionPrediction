This project predicts U.S. recessions using an ensemble of three models:
XGBoost Regressor


Neural Network (Keras)


ARIMA Time Series Model


It uses historical macroeconomic indicators from FRED and combines model outputs to estimate the probability of recession.
 How to Run
Requirements
Make sure you have the following Python packages installed:
pip install pandas numpy matplotlib seaborn scikit-learn xgboost keras tensorflow statsmodels fredapi tqdm

Steps
Open the notebook: recession_ensemble.ipynb


Run all cells from top to bottom


The notebook automatically:


Downloads the dataset from FRED


Trains the models


Evaluates them


Plots the ROC curve, confusion matrix, and recession timeline

What You'll See
Metrics: MAE, MSE, RMSE, R², ROC AUC, Brier Score


Plots: ROC curve, confusion matrix, prediction timeline


Training log: NN training loss shown every 5 epochs


Static and Rolling Backtest Results




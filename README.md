# Stock Price Prediction and EDA Project

This repository features a comprehensive project that combines an in-depth Exploratory Data Analysis (EDA) with a stock price prediction model. The project is divided into two main parts:

- **EDA:** Detailed analysis and visualizations of the dataset.
- **Prediction Model:** A machine learning model leveraging an LSTM-based architecture for forecasting stock prices, developed and trained using Google Colab for efficient processing.

## Project Highlights

- **Blog Posts:**  
  - [Optimizing Portfolios: A Sherlockian Twist on the NYSE Dataset](https://medium.com/@aamilkhaan7/optimizing-portfolios-a-sherlockian-twist-on-the-nyse-dataset-a3740e0c59b5)  
  - [Finance Meets Python: Cracking the Code for Smart Investments](https://medium.com/@hamzashak66/finance-meets-python-cracking-the-code-for-smart-investments-cb500e8f4938)

- **Google Drive Storage:**  
  - Models are saved in the `Models` folder.
  - Predictions and evaluation metrics (loss and RMSE) are stored as CSV files in the `Results` folder.
  - The data files used are also present in the drive folder.
  - [Access the full Google Drive here](https://drive.google.com/drive/folders/1wyaEdTy3q0YAxslaitGCI6GmJM99O0wH?usp=drive_link)

- **Reproducibility:**  
  The notebook is fully self-contained with clearly separated sections for EDA and model training. Training and prediction cells are skipped by default (controlled by a boolean flag) to speed up execution, but can be enabled if you wish to re-run the training process.

## Model Architecture

- The prediction component utilizes an LSTM-based model to capture temporal dependencies in the stock data, offering robust performance for time-series forecasting.

Feel free to explore, experiment, and use this project as a reference for integrating EDA with predictive modeling.

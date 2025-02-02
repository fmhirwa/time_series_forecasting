# time_series_forecasting
https://www.kaggle.com/competitions/alu-jan25-air-quality-forecasting/overview

# Air Quality Forecasting using LSTM

This repository contains the implementation of **Time Series Forecasting** for **PM2.5 Air Quality Prediction** using **LSTM networks**. The project is part of a machine learning assignment and involves data preprocessing, model training, hyperparameter tuning, and evaluation.

## 📂 Files Overview
- `train.csv` & `test.csv` – The datasets used for training and testing.
- `time_series_florent.ipynb` – The main Colab notebook containing data preprocessing, model training, and evaluation.
- `submission.csv` – The final submission file for Kaggle.
- `experiment_summary_table.csv` – Contains results of multiple experiments for model tuning.

## 🚀 Getting Started
### 1️⃣ Load Required Files
Before running the notebook, **ensure that `train.csv` and `test.csv` are uploaded to the runtime**. If using Google Colab, you can upload files manually or use Google Drive integration.

### 2️⃣ Recommended Runtime Settings
- **Enable GPU:** In Colab, go to **Runtime** → **Change runtime type** → **Select GPU**.  
- **Python Version:** Ensure you are using **Python 3.10 or later**.

### 3️⃣ Key Experiment Details
- The model uses **two LSTM layers (128 and 64 units)** with dropout and the **Adam optimizer**.
- RMSE is used as the evaluation metric.
- The `submission.csv` file is generated at the end and should match the Kaggle format.

## 📌 Important Notes
- If facing memory issues, reduce batch size in training.
- Ensure dependencies (`tensorflow`, `pandas`, `numpy`, `matplotlib`, `scikit-learn`) are installed before running the notebook.
- Check the **experiment table** for insights into model performance.

---

Good luck with ALU and Happy coding! 🚀

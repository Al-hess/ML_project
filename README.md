# Temperature Prediction in Bern

## 📌 Overview

This project predicts temperatures in Bern (Switzerland) for 12h, 24h, and 48h ahead using meteorological data from 10 Swiss cities. It's a multi-output regression task evaluated using Mean Absolute Error (MAE).

## 🎯 Objective

Develop machine learning models to forecast future temperatures based on historical weather data from multiple locations.

## 📊 Dataset

The dataset includes weather measurements from 10 Swiss cities. (Note: Due to size constraints, the raw data files are not included in this repository. You can find similar datasets on Kaggle or run the notebook with your own data.)

## 🛠️ Tools

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn

## 📈 Key Results

The notebook explores various models including Linear Regression, Ridge, Lasso, Decision Trees, Random Forest, Gradient Boosting, and XGBoost. Performance is evaluated using cross-validation and MAE scores.

*(Run the notebook to see detailed results, plots, and model comparisons.)*

## ▶️ How to Run

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Obtain the dataset (train and test CSV files)
4. Open the notebook in Jupyter and run all cells

## 📁 Structure

* `ML_project/Notebook/`: Jupyter notebook with the full analysis
* `src/`: Additional scripts (if any)
* `requirements.txt`: Python dependencies

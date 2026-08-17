#  Laptop Price Prediction with Machine Learning

##  Overview
This repository contains an end-to-end data analysis and machine learning pipeline designed to predict laptop prices based on their technical hardware specifications. The workflow covers extensive data preprocessing, exploratory data analysis (EDA), and targeted feature engineering—extracting granular features such as CPU clock speed (GHz), Screen PPI (Pixels Per Inch), and distinct memory storage allocations (SSD, HDD, Flash Storage, Hybrid). Multiple regression algorithms were benchmarked, with **Gradient Boosting Regressor** achieving the highest performance ($R^2 \approx 82.3\%$).

##  Key Steps & Methodology
- **Data Preprocessing & Cleaning:** Handled messy technical string data, standardizing storage configurations and operational systems.
- **Feature Engineering:** Calculated Screen Resolution / PPI, parsed CPU clock frequencies, and split mixed hardware memory formats into numerical metrics.
- **Model Evaluation:** Benchmarked over 10+ regression models (Linear Models, Tree-based ensembles, XGBoost, and SVR) evaluated via $R^2$, RMSE, and MAE metrics.

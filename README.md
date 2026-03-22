# Machine Learning Algorithms and Model Evaluation

Comprehensive graduate-level machine learning course portfolio covering the full ML lifecycle across 10 labs — from regression diagnostics and EDA through classical supervised/unsupervised learning, regularization, neural networks, CNNs, LSTMs, and a deep learning final project. All labs are implemented in Python with Jupyter notebooks, written reports, and output visualizations.

**Primary dataset:** Sephora product reviews (~500K+ records across segmented CSV files) with features including ratings, recommendations, skin attributes, and pricing.

---

## Skills Demonstrated

- **Regression Diagnostics** — Assumption testing: normality (Shapiro-Wilk), heteroscedasticity (Breusch-Pagan), autocorrelation (Durbin-Watson), multicollinearity (VIF)
- **Regularization** — Ridge, Lasso, and Elastic Net regression with GridSearchCV hyperparameter tuning and model comparison
- **Exploratory Data Analysis** — Distribution analysis, correlation matrices, box plots, and statistical summaries
- **Clustering** — K-means clustering with elbow method, hierarchical clustering with dendrograms
- **Unsupervised Learning** — KNN, decision trees, Naive Bayes, SVM, association rule mining
- **Neural Networks** — Feedforward neural network (FNN) implementation in PyTorch with Adam optimizer
- **CNNs** — Convolutional neural network architecture for structured data prediction
- **LSTM** — Long short-term memory model for sequential time series forecasting
- **Deep Learning Pipeline** — End-to-end comparison of FNN, CNN, and LSTM on product rating prediction
- **Model Evaluation** — Cross-validation, confusion matrices, MSE/RMSE/R²/MAE/MAPE, ROC curves

---

## Repository Structure

```text
machine-learning-algorithms-and-model-evaluation/
├── README.md
├── data/
│   ├── product_info.csv
│   └── product_monthly_panel.csv
├── docs/
│   └── data_collection_assignment.docx
├── lab1_regression_diagnostics/
├── lab2_regularization_models/
├── lab3_exploratory_data_analysis/
├── lab4_clustering_analysis/
├── lab5_unsupervised_learning_models/
├── lab6_model_training_pipeline/
├── lab7_neural_network_models/
├── lab8_lstm_time_series_model/
├── midterm_machine_learning_analysis/
└── deep-learning-product-rating-prediction/
```

Each lab folder contains a Python script (`.py`), Jupyter notebook (`.ipynb`), written report (`.docx`), and output visualizations (`.png`).

---

## Lab Summaries

| Lab | Topic | Key Techniques |
|-----|-------|----------------|
| Lab 1 | Regression Diagnostics | VIF, Shapiro-Wilk, Breusch-Pagan, Durbin-Watson |
| Lab 2 | Regularization Models | Ridge, Lasso, Elastic Net, GridSearchCV |
| Lab 3 | Exploratory Data Analysis | Distributions, correlations, summary statistics |
| Lab 4 | Clustering Analysis | K-means, elbow method, cluster profiling |
| Lab 5 | Unsupervised Learning | KNN, hierarchical clustering, decision trees, Naive Bayes, SVM, association rules |
| Lab 6 | Neural Network Training | FNN with PyTorch, Adam optimizer |
| Lab 7 | CNN Models | Convolutional neural network for rating prediction |
| Lab 8 | LSTM Time Series | Sequential LSTM model for forecasting |
| Midterm | Full ML Pipeline | Multi-algorithm comparison across clustering, classification, and association |
| Final | Deep Learning | FNN vs CNN vs LSTM comparison on product rating prediction |

---

## Dataset Note

The large Sephora review CSV files (up to 270MB each) are excluded from this repository due to GitHub file size limits. The dataset is publicly available on Kaggle. The smaller aggregated files (`data/product_info.csv`, `data/product_monthly_panel.csv`) are included.

---

## Tools & Technologies

`Python` `Jupyter Notebook` `scikit-learn` `PyTorch` `TensorFlow/Keras` `pandas` `NumPy` `matplotlib` `seaborn` `statsmodels` `GridSearchCV` `LSTM` `CNN` `FNN`

---

## About This Repository

This repository is part of a broader data and analytics portfolio. The work here reflects applied skills in machine learning and predictive modeling directly relevant to roles in:

- Data Science
- Machine Learning Engineering
- Data Analysis
- Business Intelligence Engineering
- Analytics Engineering

🩺 Breast Cancer Prediction Model

A Machine Learning project that predicts whether a tumor is benign or malignant using clinical features from the Breast Cancer Wisconsin dataset.

📌 Overview

Early diagnosis of breast cancer significantly increases the chances of successful treatment. This project uses machine learning techniques to build a predictive model that can classify breast cancer tumors based on their characteristics.

This model was trained using the Breast Cancer Wisconsin Diagnostic Dataset (WDBC), which contains features computed from digitized images of breast mass samples.

🎯 Project Objectives

Build a machine learning model to classify tumor type

Perform data cleaning, exploratory data analysis (EDA), and visualization

Train and evaluate different ML algorithms

Select the best-performing model

Deploy or integrate the model for real-time predictions

🧠 Dataset Information

The dataset contains 569 samples and 30 numerical features, including:

Radius

Texture

Perimeter

Area

Smoothness

Compactness

Symmetry

Fractal dimension

Target Variable:

0 → Malignant

1 → Benign

🔧 Technologies & Libraries Used

Python

NumPy

Pandas

Matplotlib / Seaborn

Scikit-learn

Streamlit (if deployed)

Pickle (for model saving)

📊 Model Building Steps

Data Loading & Understanding

Data Preprocessing

Handling missing values

Feature scaling using StandardScaler

Exploratory Data Analysis (EDA)

Correlation heatmap

Distribution plots

Outlier detection

Model Training
Algorithms tried:

Logistic Regression

Random Forest

SVM

KNN

XGBoost (optional)

Model Evaluation

Accuracy Score

Precision, Recall, F1-Score

Confusion Matrix

Final Model Selection
The best model is saved as breast_cancer_model.pkl

📈 Performance Metrics (Example)
Metric	Score
Accuracy	97%
Precision	96%
Recall	97%
F1 Score	96%

📌 Conclusion

This machine learning model can help in assisting the early prediction of breast cancer using clinical characteristics. It provides a reliable and efficient approach for medical decision support systems.

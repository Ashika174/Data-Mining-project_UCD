# Data-Mining-project_UCD
# Fraud Detection Using LightGBM  
A Machine Learning Project for Classifying Fraudulent Transactions  
> Developed as part of an academic business analytics project

---

## Project Overview

This project applies machine learning techniques to detect fraudulent activities in a transaction dataset. Using LightGBM (LGBM), a high-performance gradient boosting framework, the model is trained to classify whether a transaction is fraudulent based on various features.

---

## Files in the Repository

- `Fraud_Detection.ipynb` – Main Jupyter Notebook with full data exploration, feature engineering, model training, and evaluation.
- `transaction_dataset.csv` – Input dataset containing transaction data and fraud labels.
- `lgb_model.pkl` – Saved LightGBM model for reuse and inference.
- `README.md` – You’re here! This file provides an overview of the project.

---

## Key Objectives

- Perform exploratory data analysis (EDA) on transaction data.
- Engineer relevant features to improve model performance.
- Train and evaluate a LightGBM classifier.
- Save and reload the trained model using `joblib` or `pickle`.
- Analyze performance using accuracy, ROC-AUC, confusion matrix, and classification report.

---

## Technologies Used

- Python 3
- Pandas
- NumPy
- Scikit-learn
- LightGBM
- Matplotlib & Seaborn (for visualization)
- Pickle / Joblib (for model serialization)

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fraud-detection-lightgbm.git
   cd fraud-detection-lightgbm
2. Install dependencies
   ``` bash
   pip install -r requirements.txt
3. Open Jupyter Notebook
   ``` bash
   jupyter notebook Fraud_Detection.ipynb
4. To reuse the trained model
   ``` bash
   import pickle
    with open('lgb_model.pkl', 'rb') as file:
    model = pickle.load(file)


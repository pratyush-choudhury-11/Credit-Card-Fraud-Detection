Credit Card Fraud Detection
1. Project Overview

Credit card fraud is a growing problem that causes significant financial losses each year. This project focuses on building a Machine Learning model to detect fraudulent credit card transactions by analyzing real-world data and identifying abnormal patterns.

The objective is to accurately classify transactions as fraudulent or legitimate, even when the dataset is extremely imbalanced.

2. Features

Complete data preprocessing

Exploratory Data Analysis (EDA)

Feature scaling and transformation

Handling data imbalance (SMOTE / undersampling)

Testing multiple ML models

Evaluation using Precision, Recall, F1-Score, Accuracy, ROC-AUC

Final optimized model for fraud detection

3. Technologies Used

Python

NumPy

Pandas

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

4. Dataset

The dataset used is publicly available on Kaggle:

Dataset Link:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Download the dataset and place creditcard.csv in your project directory.

5. Model Workflow

Load and explore dataset

Preprocess data

Check missing values

Feature scaling

Remove outliers

Handle class imbalance:

SMOTE

Undersampling

Train models:

Logistic Regression

Random Forest

Decision Tree

XGBoost (optional)

Evaluate results

Generate fraud prediction

6. Results

High Recall achieved, which is crucial for fraud detection

ROC-AUC score shows strong model performance

Good balance of Recall and Precision



7. How to Run
Step 1 — Clone the Repository
git clone https://github.com/pratyush-choudhury-11/Credit-Card-Fraud-Detection

Step 2 — Install Dependencies
pip install -r requirements.txt

Step 3 — Run the Notebook
jupyter notebook


Open Credit_Card_Fraud_Detection.ipynb and run all cells.

8. Project Structure
├── Credit_Card_Fraud_Detection.ipynb
├── creditcard.csv
├── README.md
└── requirements.txt

9. Live Project Link

Your GitHub project repository:

👉 LIVE LINK:
https://github.com/pratyush-choudhury-11/Credit-Card-Fraud-Detection

10. Future Improvements

Deploy model using Flask / FastAPI

Add UI dashboard using Streamlit

Use deep learning models

Build real-time fraud detection system

11. License

This project is open-source and free for learning and research purposes.

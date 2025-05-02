💳 Credit Card Fraud Detection using Machine Learning
This project uses supervised machine learning techniques to detect fraudulent credit card transactions. The dataset is highly imbalanced, so special preprocessing steps like normalization and SMOTE (Synthetic Minority Oversampling Technique) are used to improve model performance.

📁 Dataset
The dataset contains credit card transactions made by European cardholders in September 2013. It includes 284,807 transactions with 31 features, and the target variable Class indicates fraud (1) or genuine (0) transactions.

Features are PCA-anonymized (V1–V28)

Amount is the transaction value

Time is the time in seconds from the first transaction

Dataset Source: Kaggle - Credit Card Fraud Detection

🧠 Models Used
Logistic Regression

Random Forest Classifier

⚙️ Steps Performed
Data Loading and Exploration

Feature Scaling (StandardScaler on Amount)

Train-Test Split (80-20 with stratified sampling)

Class Imbalance Handling using SMOTE

Model Training (Logistic Regression and Random Forest)

Model Evaluation:

Confusion Matrix

Precision, Recall, F1-score

Prediction Results:

Separate true positives, false positives, etc.

Export results to .csv files

📊 Evaluation Metrics
Metric	Description
Accuracy	Overall prediction correctness
Precision	How many predicted frauds were actually fraud
Recall	How many actual frauds were correctly identified
F1-Score	Harmonic mean of precision and recall
Focus is on Recall for fraud detection (we don't want to miss frauds).

📦 Files Included
creditcard.csv – Raw data file (not included in repo)

fraud_detection.ipynb – Full Colab notebook

true_positives.csv, false_positives.csv – Result exports


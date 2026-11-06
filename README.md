"""
OBJECTIVE:
Predict whether a bank customer will subscribe to a term deposit (Yes / No).

DATASET:
- Bank Marketing Dataset
- 45,211 Records
- Target Column: y (Yes / No)

WORKFLOW:
1. Data Loading and Understanding
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Outlier Detection and Handling
5. Feature Engineering
6. Categorical Encoding (One-Hot Encoding)
7. Correlation Analysis
8. Feature and Target Selection
9. Train-Test Split (80:20)
10. Random Forest Model Training
11. XGBoost Model Training
12. Model Evaluation (Accuracy, Precision, Recall, F1-Score)
13. Confusion Matrix Analysis
14. ROC Curve and AUC Analysis
15. Final Model Selection (XGBoost)
16. New Customer Prediction
17. Subscription Probability Prediction

FINAL MODEL: XGBoost Classifier

PERFORMANCE:
- Accuracy: 91.56%
- Precision (Yes): 62%
- Recall (Yes): 45%
- F1-Score (Yes): 52%
- ROC-AUC: 93.08%

MODEL COMPARISON:
- Random Forest Accuracy: 91.25%
- XGBoost Accuracy: 91.56%

BUSINESS VALUE:
Helps banks identify potential customers,
improve targeted marketing campaigns,
and reduce unnecessary marketing efforts.
"""

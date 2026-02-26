📊 Customer Churn Prediction Using Machine Learning
📌 Project Overview

This project focuses on predicting customer churn using Machine Learning techniques. The objective is to identify customers who are likely to leave a service based on historical data such as tenure, contract type, monthly charges, and other customer-related features.
Early churn prediction helps businesses take proactive measures to retain customers and reduce revenue loss.

🎯 Problem Statement

Customer churn is a major challenge for subscription-based businesses.
The goal of this project is to build and compare machine learning models to accurately predict whether a customer will churn or not.

🗂️ Dataset

The dataset contains customer information including:
Customer tenure
Contract type
Monthly charges
Payment method
Internet service
Total charges
Churn (Target variable)
Target Variable:
0 / False → Customer did not churn
1 / True → Customer churned

⚙️ Technologies Used

Python
Pandas
NumPy
Scikit-learn
Matplotlib / Seaborn

🧠 Machine Learning Models Used

1️⃣ Logistic Regression
Data scaling applied using StandardScaler
Achieved:
Accuracy: ~74%
ROC-AUC: ~0.84
Good recall for churn class

2️⃣ Random Forest (Tuned)
Hyperparameter tuning using GridSearchCV
Achieved:
Accuracy: ~77%
ROC-AUC: ~0.84
Better balance between precision and recall

📊 Model Evaluation Metrics

The following metrics were used to evaluate model performance:
Accuracy
Balanced Accuracy
Precision
Recall
F1-Score
ROC-AUC Score
Confusion Matrix

📌 Future Improvements

Handle class imbalance using SMOTE
Try advanced models like XGBoost
Perform feature engineering
Deploy the model using Flask or Streamlit


📈 Results & Conclusion

Both models performed well with similar ROC-AUC (~0.84).
Random Forest achieved slightly higher overall accuracy.

Logistic Regression showed strong recall for identifying churn customers.

Random Forest was selected as the final model due to better overall balance.

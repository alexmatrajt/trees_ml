# Customer Churn Prediction – Telco Dataset

This project predicts customer churn using the Telco Customer Churn dataset from IBM Sample Data Sets.

#### Models Trained
🌳 Decision Tree – with class weighting and hyperparameter tuning

🌲 Random Forest – with grid search and feature importance analysis

⚡ XGBoost – using scale_pos_weight to handle class imbalance

Performance was evaluated using F1-score, precision, recall, and confusion matrices. A SHAP analysis was conducted to interpret XGBoost predictions and identify the most influential features.

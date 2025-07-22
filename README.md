💳 Data-Level Imbalance Handling Techniques: A Comparative Study on Credit Card Fraud Detection
🔗 Presentation

This project aims to compare multiple data imbalance handling techniques and machine learning models that yield an efficient credit card fraud detection system — capable of identifying whether each transaction is legitimate or fraudulent.

This project was originally created as a joint university thesis by Malak Hatem, Masa Tantawy, and Moustafa El Mahdy (myself).
This is a personal fork for portfolio and reference purposes, with full credit to all contributors.
📦 Original repository: github.com/Masa-Tantawy/Data-Level-Imbalance-Handling-Techniques-A-Comparative-Study-on-Credit-Card-Fraud-Detection

🛠️ Imbalance Handling Techniques
To handle data imbalance before model training, the following methods were explored:
➡️ Oversampling
➡️ Undersampling
➡️ Oversampling followed by Undersampling

Specifically, the techniques used include:

Undersampling:

Random Undersampling (RUS)

TomekLinks

Oversampling:

Random Oversampling (ROS)

SMOTE

Oversampling + Undersampling:

SMOTE + TomekLinks (SmoteTomek)

SMOTE + Edited Nearest Neighbors (SmoteENN)

🤖 Machine Learning Models Used
Once the data was preprocessed, the following supervised ML models were applied:

Random Forest

Extreme Gradient Boosting (XGBoost)

Light Gradient Boosting Machine (LightGBM)

📊 Evaluation Approach & Metrics
Two evaluation approaches were employed:

80%-20% Train-Test Split

5-Fold Cross Validation

Since fraudulent transactions are the main focus, models are optimized to minimize false negatives (i.e., avoid missing any fraud).
Thus, the chosen performance metrics are:

Precision

Recall

F1 Score

📁 Dataset Access
All required datasets can be found here:
👉 Google Drive Folder

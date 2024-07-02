# Data-Level-Imbalance-Handling-Techniques-A-Comparative-Study-on-Credit-Card-Fraud-Detection

This paper aims to compare multiple data imbalance handling techniques and machine learning models that yield an efficient credit card fraud detection system that can identify
whether each transaction is legitimate or fraudulent. To handle data imbalance before model training, oversampling, undersampling, and oversampling followed by undersampling are used.
Particularly, these are the techniques used:   
1. Undersampling: Random Undersampling (RUS) and Tomeklinks
2. Oversampling: Random Oversampling (ROS) and Smote
3. Oversampling followed by Undersampling: Smote + Tomek (SmoteTomek) and Smote + ENN (Smoteen)

After the data is pre-processed, three supervised machine learning models are used:   
- Random Forest
- Extreme Gradient Boosting (XGBoost)
- Light Gradident Boosting Machine (LightGBM)

To evaluate the model, 2 approaches were used:
- 80%-20% Train-Test Split
- 5-fold Cross Validation
Since fraudulent transactions are of interest, it is more important for the models to correctly predict fraudulent transactions compared to
legitimate ones. In other words, it is critical that the model is unable to miss any fraud among the transactions and correctly identify it rather than labelling a legitimate transaction as fraudulent. Hence, the selected metrics that focus on these objectives are:   
- Precision
- Recall
- F1 score

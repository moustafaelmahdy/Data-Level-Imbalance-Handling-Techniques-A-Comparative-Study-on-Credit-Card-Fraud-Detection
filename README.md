# Data-Level-Imbalance-Handling-Techniques-A-Comparative-Study-on-Credit-Card-Fraud-Detection
[Presentation](https://pitch.com/v/thesis-presentation-wmzd5h)

This Project aims to compare multiple data imbalance handling techniques and machine learning models that yield an efficient credit card fraud detection system that can identify
whether each transaction is legitimate or fraudulent. 

This project was originally created as a joint university thesis project by Malak Hatem, Masa Tantawy and Moustafa El Mahdy (myself). This is a personal fork for portfolio and reference purposes, with full credit to all contributors. Original repository: https://github.com/Masa-Tantawy/Data-Level-Imbalance-Handling-Techniques-A-Comparative-Study-on-Credit-Card-Fraud-Detection

To handle data imbalance before model training, oversampling, undersampling, and oversampling followed by undersampling are used.
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

All the required datasets can be found [here](https://drive.google.com/drive/folders/1785b9aGd_wx_uBPkMSnZNKdmYrr8OeU0?usp=drive_link).

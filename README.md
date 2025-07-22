# 🎯 **Data-Level-Imbalance-Handling-Techniques: A Comparative Study on Credit Card Fraud Detection**
[📊 **Presentation**](https://pitch.com/v/thesis-presentation-wmzd5h)

This project aims to compare multiple _data imbalance handling techniques_ and _machine learning models_ to build an efficient credit card fraud detection system that can identify whether each transaction is **legitimate** or **fraudulent**. 

> _Originally created as a joint university thesis project by **Malak Hatem**, **Masa Tantawy**, and **Moustafa El Mahdy** (myself)._  
> _This is a personal fork for portfolio and reference purposes, with full credit to all contributors._  
> 🔗 __Original repository__: https://github.com/Masa-Tantawy/Data-Level-Imbalance-Handling-Techniques-A-Comparative-Study-on-Credit-Card-Fraud-Detection

---

## ⚠️ **Data Imbalance Handling Techniques**

To handle imbalance before model training, the following techniques were explored:

__1. Undersampling:__  
- Random Undersampling (RUS)  
- Tomek Links  

__2. Oversampling:__  
- Random Oversampling (ROS)  
- SMOTE  

__3. Oversampling followed by Undersampling:__  
- SMOTE + Tomek (SmoteTomek)  
- SMOTE + ENN (SmoteENN)  

---

## 🤖 **Machine Learning Models Used**

After pre-processing, the following supervised ML models were trained:  
- **Random Forest**  
- **Extreme Gradient Boosting (XGBoost)**  
- **Light Gradient Boosting Machine (LightGBM)**  

---

## 📈 **Evaluation Strategy**

Two evaluation approaches were used:  
- _80%-20% Train-Test Split_  
- _5-fold Cross Validation_

Since fraudulent transactions are the focus, it was critical that the models minimize **false negatives** (missed fraud).  
So, the evaluation metrics emphasized were:  
- **Precision**  
- **Recall**  
- **F1 Score**

---

## 📂 **Datasets**

All required datasets can be found here:  
[👉 Click to Access Dataset Folder](https://drive.google.com/drive/folders/1785b9aGd_wx_uBPkMSnZNKdmYrr8OeU0?usp=drive_link)


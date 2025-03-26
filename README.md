# 🏠 HOUSE PRICE PREDICTION - ADVANCED REGRESSION

## 🏆 OVERVIEW  
🚀 This project aims to **predict house sale prices** using advanced regression techniques.  
💡 It analyzes multiple property features to understand how factors like lot area, building class, and zoning influence the final sale price.

---

## 📂 DATASET  
📸 **Key Attributes:**  
✅ **SalePrice** – The target variable representing the property’s sale price.  
✅ **MSSubClass** – The building class.  
✅ **MSZoning** – General zoning classification.  
✅ **LotFrontage** – Linear feet of street connected to the property.  
✅ **LotArea** – Lot size in square feet.  
✅ **Street** – Type of road access.  
✅ **Alley** – Type of alley access.  
✅ **LotShape** – General shape of the lot.  

📌 **Preprocessing Techniques:**  
🔹 Handling missing values.  
🔹 Feature engineering & transformation.  
🔹 Normalization & scaling.  
🔹 Train-test splitting.

---

## ⚡ MODELS & ANALYSIS

### 🔵 **Regression Models Evaluated**  
✔️ **Linear Regression**  
✔️ **Random Forest Regressor**  
✔️ **Gradient Boosting Regressor**  
✔️ **XGBoost Regressor (Best Individual Model)**  

### 🔴 **Ensemble Methods**  
✔️ **Stacking Regressor** – Combines predictions from multiple base models for improved accuracy.  
✔️ **Voting Regressor** – Averages predictions from several models to reduce variance.

📊 **Key Insights:**  
✅ **XGBoost** delivers high prediction accuracy among individual models.  
✅ **Stacking and Voting Ensembles** further improve performance by leveraging strengths of multiple algorithms.  
✅ Feature importance analysis helps identify key drivers of house prices.

---

## 🛠 INSTALLATION  
📥 **Install dependencies:**  
```bash
pip install numpy pandas scikit-learn xgboost matplotlib

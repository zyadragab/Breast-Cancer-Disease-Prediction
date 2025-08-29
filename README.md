# 🩺 Breast Cancer Prediction  

Machine Learning project to predict breast cancer (*malignant vs benign*) using Logistic Regression, Random Forest, SVM, and XGBoost.  

---

## 📊 Dataset  
- *Source:* Breast Cancer dataset from sklearn (Wisconsin Diagnostic Breast Cancer).  
- *Features:* 30 numerical features (e.g., mean radius, mean texture, mean smoothness).  
- *Target Classes:*  
  - 0 = malignant (cancerous)  
  - 1 = benign (non-cancerous)  

---

## 🔎 Approach  

1. *Data Loading & Exploration*  
   - Loaded the Breast Cancer dataset from sklearn.  
   - Checked dataset structure using .info() and .describe().  
   - Verified there are no missing values (.isnull().sum()).  
   - Visualized class distribution and feature correlations.  

2. *Data Preprocessing*  
   - Standardized numerical features using StandardScaler.  
   - Performed Train/Test split (70% training – 30% testing).  

3. *Model Training*  
   - Trained four classification algorithms:  
     - Logistic Regression  
     - Random Forest  
     - Support Vector Machine (SVM)  
     - XGBoost  

4. *Evaluation*  
   - Compared models using *Accuracy, Precision, Recall, and F1-Score*.  
   - Visualized results with *Confusion Matrices* and a *bar chart comparison*.  

---

## 🤖 Algorithms Used  
- 🔹 Logistic Regression  
- 🌲 Random Forest  
- 📐 Support Vector Machine (SVM)  
- ⚡ XGBoost  

---

## 📏 Evaluation Metrics  
- ✅ Accuracy  
- ✅ Precision  
- ✅ Recall  
- ✅ F1 Score  

---

## 🏆 Results  
| Model                | Accuracy | Precision | Recall | F1 Score |  
|-----------------------|----------|-----------|--------|----------|  
| Logistic Regression   | 98%      | 99%       | 99%    | 99%      |  
| Random Forest         | 93%      | 94%       | 95%    | 94%      |  
| SVM                   | 97%      | 98%       | 98%    | 98%      |  
| XGBoost               | 96%      | 95%       | 99%    | 97%      |  

---

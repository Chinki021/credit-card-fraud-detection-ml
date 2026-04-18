# 💳 Credit Card Fraud Detection using Machine Learning

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Project-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

🔗 **Open in Google Colab**  
Credit_Card_Fraud_Detection_using_ml.ipynb - Colab https://share.google/9R1U475WcewXDp12J

---

## 📌 Overview

Credit card fraud is a major issue in the financial industry, causing huge losses every year.  
This project builds a **machine learning model to detect fraudulent transactions** from highly imbalanced data.

💡 **Goal:** Identify fraudulent transactions accurately while minimizing false positives.

---

## 🧠 Problem Statement

Given transaction data, predict:

👉 **Fraud (1) or Legitimate (0)**

---

## 📊 Dataset Details

- 📁 Transactions: **284,807**
- 🎯 Target Variable: **Class (0 = Legit, 1 = Fraud)**
- ⚠️ Highly Imbalanced Dataset

### Features:
- `Time`  
- `Amount`  
- `V1` to `V28` (PCA transformed features)  

---

## ⚙️ Tech Stack

| Category        | Tools Used |
|----------------|----------|
| Language       | Python |
| Data Handling  | Pandas, NumPy |
| ML Model       | Scikit-learn (Logistic Regression) |

---

## 🔄 Workflow

### 🧹 Data Preprocessing
- Loaded dataset from ZIP file  
- Checked data structure  
- Handled imbalance manually  

### ⚖️ Handling Imbalance
- Separated fraud and normal transactions  
- Applied **under-sampling** to balance the dataset  

### 🤖 Model Training
- Logistic Regression model  

### 📊 Evaluation
- Accuracy Score  

---

## 🤖 Model Used

| Model                | Description |
|---------------------|------------|
| Logistic Regression | Baseline classification model |

---

## 📈 Key Insights

✔ Fraudulent transactions are **extremely rare** compared to normal ones  
✔ Data imbalance significantly affects model performance  
✔ Even simple models can perform well with proper preprocessing  

---

## 🏆 Results

- Model successfully detects fraudulent transactions  
- Achieved reliable performance on balanced dataset  

---

## 🚀 Future Improvements

- Use advanced models (Random Forest, XGBoost, Neural Networks)  
- Apply SMOTE instead of under-sampling  
- Improve evaluation using Precision, Recall, F1-score  
- Deploy as a fraud detection system  

---

## 👩‍💻 Author

**CHINKI RAJ**  

---

## ⭐ Why This Project Matters

- ✅ Real-world financial problem  
- ✅ Handles highly imbalanced data  
- ✅ End-to-end ML pipeline  
- ✅ Practical fraud detection use case  

---

## 🙌 Support

If you found this project useful, consider giving it a ⭐ on GitHub!

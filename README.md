# 💳 Credit Card Fraud Detection  

A machine learning project to detect fraudulent credit card transactions using classification models and class imbalance handling techniques.  

---

## 📁 Project Files  

- `credit_card_fraud_detection.ipynb` — Jupyter Notebook with full code  
- `README.md` — This documentation file  
- **Dataset not included** due to size. See dataset link below.  

---

## 📉 Dataset Source  

We used the public credit card fraud dataset available on **Kaggle**:  

📂 **[Credit Card Fraud Detection Dataset on Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)**  
- Size: ~140MB  
- Contains anonymized credit card transactions (284,807 records)  

---

## 🚀 Features  

- 📊 Preprocessing and feature scaling  
- ⚖️ Class imbalance handled using **SMOTE**  
- 🔍 Model training with **Random Forest**  
- 📈 Evaluation: Confusion Matrix, Precision, Recall, F1-Score  

---

## 🧠 Technologies Used  

- Python 3  
- Jupyter Notebook  
- Libraries:  
  - `pandas`, `numpy`, `matplotlib`, `seaborn`  
  - `scikit-learn`  
  - `imblearn` (for SMOTE)  

---

## ⚙️ Workflow  

1. Load dataset and explore class imbalance  
2. Normalize features using `StandardScaler`  
3. Apply SMOTE to balance the data  
4. Split into training and testing sets  
5. Train a `RandomForestClassifier`  
6. Predict and evaluate  

---

## 📊 Example Results  

Confusion Matrix:  
[[85135 14]
[ 0 85440]]

Classification Report:  
          precision    recall  f1-score   support

       0       1.00      1.00      1.00     85149
       1       1.00      1.00      1.00     85440

accuracy                           1.00    170589

macro avg 1.00 1.00 1.00 170589
weighted avg 1.00 1.00 1.00 170589


> Results may vary depending on sampling and model parameters.  

---

## 👨‍💻 Author  

- **Shreyas D P**  
- GitHub: [Shreyas-tech-coder](https://github.com/Shreyas-tech-coder)  

---

## 📜 License  

This project is for academic and learning purposes only.  
Dataset is licensed and owned by the original authors on Kaggle.  

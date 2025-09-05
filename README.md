# Credit Card Fraud Detection using Machine Learning

##  Project Overview
This project applies **machine learning techniques** to detect fraudulent credit card transactions.  
Fraudulent transactions are very rare (0.17%) but critical to detect to reduce financial losses.

---

## 🔹 Dataset
- Source: [Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)  
- Transactions: 284,807  
- Fraud Cases: 492 (0.17%)  
- Features: V1–V28 (PCA-transformed), Time, Amount  
- Target: Class (0 = Legitimate, 1 = Fraud)  

---

## 🔹 Methodology
1. Data Exploration & Preprocessing  
2. Train-Test Split (80/20)  
3. Models Used: Logistic Regression, Random Forest  
4. Handling Class Imbalance using SMOTE  
5. Evaluation with ROC, PR Curve, and Confusion Matrix  

---

## 🔹 Results
- Logistic Regression: Baseline model, weaker recall  
- Random Forest: Better AUC, stronger detection  
- Random Forest + SMOTE: Best performance (balanced recall & precision)  

📊 Best Model → **Random Forest + SMOTE**

---

## 🔹 Deliverables
- 📓 Notebook: `credit_card_fraud_detection.ipynb`  
- 📑 Presentation: `Credit_Card_Fraud_Detection_Presentation.pptx`  
- ⚙️ Requirements: `requirements.txt`  

---

## 👩‍💻 Author
**Malleswari Muthireddy**  
💼 Aspiring Data Analyst / Data Scientist  
📌 Skills: Python, Pandas, Scikit-learn, Machine Learning  

# 🚨 Fraud Detection System — Accredian Case Study  

This project implements a **Fraud Detection Model** for financial transactions, developed as part of the **Accredian Data Science Internship screening assessment**.  
The dataset contains **6.3M+ rows of transactions** with features such as balances, transaction type, and fraud labels.  

---

## 🛠️ Workflow  

- **Data Cleaning:** Checked for missing values (none found), handled categorical variables, and reduced multicollinearity by engineering new balance-difference features.  
- **Feature Engineering:** Created features such as `deltaOrig`, `deltaDest`, merchant flags, and zero-balance anomaly indicators.  
- **Model Building:**  
  - Baseline → Logistic Regression  
  - Final → **Random Forest Classifier** with class weighting for imbalance.  
- **Evaluation:** Performance assessed with Confusion Matrix, Classification Report, ROC-AUC, and Precision-Recall curves.  

---

## 📊 Results  

- **ROC-AUC:** > 0.95  
- **PR-AUC:** ~0.92  
- Very few false negatives → ensures most fraudulent transactions are detected.  
- Fraud is most common in **TRANSFER** and **CASH_OUT** transactions.  

---

## 🔐 Recommendations  

- Real-time monitoring of suspicious transaction types.  
- Two-Factor Authentication (2FA) for high-value transfers.  
- Adaptive daily transaction limits based on customer history.  
- Continuous retraining of the fraud detection model to adapt to new patterns.  

---

## 📌 Q&A Coverage  

The Jupyter Notebook also includes answers to Accredian’s screening questions:  
1. Data cleaning steps  
2. Fraud detection model description  
3. Variable selection process  
4. Model performance demonstration  
5. Key factors predicting fraud  
6. Interpretation of these factors  
7. Infrastructure-level prevention measures  
8. How to evaluate effectiveness post-implementation  

---

## 👤 Author  

**Shailesh K R**  
- Email: krshailesh627@gmail.com  
- LinkedIn: [https://www.linkedin.com/in/shailesh-kr-1a7a06256/](#)  
- GitHub: [https://github.com/Shailesh7772](#)  

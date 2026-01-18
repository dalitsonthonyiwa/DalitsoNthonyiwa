# 🏦 Loan Default Prediction using Machine Learning 📊💳

This project builds and evaluates machine learning models to **predict loan defaults** using historical loan and customer data.  
The goal is to help financial institutions **minimize credit risk, reduce financial losses, and improve loan approval decisions**.

---

## 🚀 Project Overview

- **Data Source:** `Task 3 and 4_Loan_Data.csv`
- **Objective:** Predict whether a customer will default on a loan
- **Business Goal:**  
  👉 **Maximize Recall (Sensitivity)** to catch *all potential defaulters* and avoid financial losses

---

## 🔧 Tools & Libraries

- **Python**
  - Pandas
  - NumPy
- **Visualization**
  - Matplotlib
  - Seaborn
- **Machine Learning**
  - Scikit-learn  
    - Logistic Regression  
    - Decision Tree  
    - Random Forest
- **Imbalanced Data Handling**
  - Imbalanced-learn (Over-sampling & Under-sampling)
- **Evaluation Metrics**
  - Accuracy
  - Recall
  - Precision
  - Confusion Matrix

---

## 📈 Methodology

### 1️⃣ Exploratory Data Analysis (EDA)
- Distribution of loan defaults
- Boxplots comparing financial variables vs default behavior
- Class imbalance assessment

### 2️⃣ Model Training
- Logistic Regression
- Decision Tree


### 3️⃣ Handling Class Imbalance
- Random Over-Sampling
- Random Under-Sampling

### 4️⃣ Model Evaluation
- Confusion Matrix
- Accuracy
- Precision
- Recall
- Business impact assessment

---

## ✅ Results & Insights

### 🔍 Model Performance
- **Recall (Sensitivity): 100%**
  - No false negatives
  - *No defaulters missed*
- **Precision: 99.4%**
  - Only **2 good customers** wrongly flagged
- **Accuracy: ~99.9%**
  - Extremely strong overall performance

### 💰 Financial Impact
- **Correctly flagged defaulters:** 348
- **Estimated savings:** **$3.48M**
- **Opportunity cost:**  
  - Only 2 rejected good applications (minimal impact)

---

## 🏦 Business Recommendations

- ✅ **Immediate Deployment**  
  Model performance is exceptional and production-ready.
- 🧑‍💼 **Manual Review for False Positives**  
  Add human oversight for borderline cases.
- 📊 **Ongoing Monitoring**  
  Track recall and precision to ensure long-term stability.
- ⚖️ **Risk Management**  
  Model is slightly conservative — ideal for minimizing financial risk.

---

## 📌 Future Work

- Incorporate advanced models:
  - XGBoost
  - Gradient Boosting
  - Neural Networks
- Feature engineering for deeper customer insights
- Deploy as an **API** for integration with loan management systems

---

## 💡 Key Takeaway

This project demonstrates how machine learning can deliver **real financial value** in banking:

- ❌ Zero losses from undetected defaulters
- 💵 Millions saved in prevented defaults
- ✅ High confidence in loan approval decisions

---

---

## 👤 Author

**Dalitso Nthonyiwa**  
*MSc Financial Engineering | Data Science & Quantitative Finance*

---

⭐ If you find this project useful, feel free to star the repository!






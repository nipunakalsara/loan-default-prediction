# 💳 Loan Default Prediction using Machine Learning

---

## 📌 Overview
This project develops a machine learning solution to predict whether a borrower is likely to default on a loan using historical lending data.

The objective is to support:
- Risk assessment  
- Smarter lending decisions  
- Early identification of high-risk borrowers  

---

## 🎯 Business Problem
Loan default creates financial risk for lenders.

This project aims to classify borrowers as:

- ✅ Non-Default (0)
- ⚠️ Default (1)

---

## 🗂 Dataset Features
The dataset includes borrower and loan-related variables such as:

- 💰 Income  
- 📈 Credit Score  
- 🏦 Loan Amount  
- 📉 Interest Rate  
- 🏠 Property Value  
- 📊 Debt-to-Income Ratio (DTI)  
- 📌 Loan-to-Value (LTV)

**Target Variable:** `Status`

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing
- Missing value handling  
- Categorical encoding  
- Feature scaling  
- Train-test split  
- Data leakage checks  

---

### 2️⃣ Exploratory Data Analysis
- Class distribution  
- Correlation analysis  
- Feature relationships  
- Risk pattern exploration  

---

### 3️⃣ Models Implemented
- 📍 Logistic Regression  
- 🌳 Decision Tree  
- 🌲 Random Forest  

---

### 4️⃣ Hyperparameter Tuning
Used GridSearchCV to optimize:

- max_depth  
- n_estimators  

---

## 📊 Evaluation Metrics
Models evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  
- Confusion Matrix  

### ⭐ Priority Metric:
**Recall**  
Because minimizing false negatives is critical in default-risk prediction.

---

## 🏆 Final Model
Selected Model:

**🌲 Random Forest (Tuned)**

Best Parameters:

```python
{'max_depth': None, 'n_estimators': 200}
```

---

## 🔍 Key Insights
- Credit-related variables strongly influence default behavior.  
- Tree-based models captured nonlinear patterns effectively.  
- Recall was prioritized due to financial risk considerations.  

---

## 🛠 Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📁 Project Structure

```text
Loan_Default/
├── Loan_Fixed.ipynb
├── Loan_Default.csv
├── README.md
```

---

## 📄 Reference
Link: https://drive.google.com/drive/folders/160qyA_uPfiNFgtuyVyw6x6TdAjouItSX
 

---

## 👤 Author
Your Name  
Nipuna kalsara

💡 Interests:
- Machine Learning  
- Data Analytics  
- Finance Domain Projects  

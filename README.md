# Telecom Customer Churn Prediction 📊

## 📌 Project Overview
Customer churn is one of the biggest challenges in the telecom industry. This project aims to predict whether a customer will **churn (leave the service)** or not based on their service usage, account information, and demographics.  

By identifying potential churners, telecom companies can take proactive measures to improve customer retention.

---

## 📂 Dataset
The dataset contains customer-level information such as:
- 📞 **Customer Account Details** – tenure, contract type, billing method  
- 💻 **Services Subscribed** – phone service, internet service, streaming, etc.  
- 💳 **Payment Information** – monthly charges, total charges  
- 🏷 **Target Variable** – `Churn` (Yes/No)  

---

## ⚙️ Methodology
1. **Data Preprocessing**
   - Handled missing values
   - Encoded categorical features
   - Performed feature scaling  

2. **Exploratory Data Analysis (EDA)**
   - Visualized churn distribution
   - Analyzed churn by service type, contract type, and payment method  

3. **Model Building**
   - Logistic Regression  
   - GridSearchCV
   - Cross Validation

4. **Model Evaluation**
   - Accuracy  
   - Precision, Recall, F1-score  
   - Confusion Matrix  

---

## 🚀 Results
- Best performing model: **LogisticRegression(C=100,penalty='l1',solver='liblinear')**  
- Achieved around **80~%** accuracy with balanced performance across churn and non-churn classes.  

---

## 🛠 Tech Stack
- **Python** (pandas, numpy, scikit-learn, matplotlib, seaborn)  
- **Jupyter Notebook**  
- **Machine Learning** (classification algorithms)  

---

## 📈 Future Improvements
- Hyperparameter tuning for better performance  
- Handling class imbalance using SMOTE/oversampling  
- Deploying model as a **web app** using Flask/Streamlit  
- Creating a **dashboard** for business insights  

---

## 🤝 Contribution
Contributions are welcome! Feel free to fork this repo and submit pull requests.  

# Customer_Classification
This project focuses on classifying customers based on their behavioral and demographic data using supervised machine learning techniques. The analysis and model training are performed in Google Collab for ease of access and reproducibility.
# 🧠 Customer Churn Prediction Project

## 📌 Objective
The goal of this project is to predict whether a customer is likely to **churn (leave)** or **stay**, based on demographic and transactional data such as age, gender, income, and purchase frequency.

---

## 🛠️ Tools and Libraries Used

- Python 3
- NumPy
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn

---

## 🤖 Machine Learning Model

- **Logistic Regression** (a binary classification algorithm)

### Why Logistic Regression?
It’s simple, interpretable, and effective for binary classification tasks like churn prediction.

---

## 📈 Model Performance

- **Accuracy Score:** ~<calculated_score>  
- **Evaluation Metrics:**
  - Confusion Matrix
  - Precision, Recall, F1-score

### Performance Insights
Customers with **low income** and **low purchase frequency** are more likely to churn.

---

## 📝 Project Files

- `customer_churn.py` — Main code for data loading, visualization, model training and prediction.
- `customer.csv` — Dataset used for training/testing.
- `README.md` — Project explanation and documentation.

---

## 🧪 Sample Prediction

A sample customer with the following data:
- Age: 35
- Gender: Female (1)
- Income: $37k
- Purchase Frequency: 2

**Prediction:** Likely to churn ✅

---

## 🚀 Future Work

- Add more features (e.g., customer tenure, feedback score)
- Try other ML models (e.g., Decision Trees, Random Forest, XGBoost)
- Perform hyperparameter tuning and cross-validation

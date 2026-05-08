# 📊 Customer Churn Prediction using Machine Learning

A machine learning project to predict whether a customer will churn (leave) a telecom company, using the Telco Customer Churn dataset from Kaggle.

---

## 🔍 Problem Statement

Customer churn is one of the biggest challenges in the telecom industry. The goal of this project is to build a classification model that predicts whether a customer is likely to churn based on their usage patterns and account information — enabling businesses to take proactive steps to retain customers.

---

## 📁 Dataset

- **Source:** [Telco Customer Churn - Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Rows:** 7,043 customers
- **Target Column:** `Churn` (Yes / No)
- **Features include:** tenure, MonthlyCharges, TotalCharges, Contract type, InternetService, PaymentMethod, etc.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Programming language |
| Pandas & NumPy | Data manipulation |
| Matplotlib & Seaborn | Data visualization |
| Scikit-Learn | Model building & evaluation |
| Jupyter Notebook | Development environment |

---

## 📌 Project Workflow

1. **Exploratory Data Analysis (EDA)**
   - Visualized churn distribution
   - Analyzed feature correlations
   - Identified key churn drivers (tenure, contract type, monthly charges)

2. **Data Preprocessing**
   - Handled missing values in `TotalCharges`
   - Encoded categorical variables using Label Encoding
   - Feature scaling using StandardScaler

3. **Model Building**
   - Logistic Regression
   - Random Forest Classifier
   - Decision Tree Classifier

4. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-Score)

---

## 📈 Results

| Model | Accuracy |
|-------|----------|
| Logistic Regression | ~80% |
| Decision Tree | ~79% |
| Random Forest | ~82% |

> ✅ Random Forest gave the best performance overall.

---

## 🚀 How to Run

1. Clone this repository
```bash
git clone https://github.com/codiac-690/customer-churn-prediction.git
cd customer-churn-prediction
```

2. Install required libraries
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the notebook
```bash
jupyter notebook
```

4. Run all cells in the `.ipynb` file

---

## 📂 Project Structure

```
customer-churn-prediction/
│
├── customer_churn.ipynb       # Main Jupyter Notebook
├── telco_churn.csv            # Dataset
└── README.md                  # Project documentation
```

---

## 🙋‍♀️ Author

Gurpreet Kaur
📧 gk798344@gmail.com  
 | [GitHub](https://github.com/codiac-690)

---

## 📚 Reference

Project inspired by [Siddhardhan's YouTube Tutorial - Project 22](https://youtu.be/qNglJgNOb7A)

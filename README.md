# Customer Churn Prediction

## Project Overview
This project predicts whether a customer will leave a telecom service (churn) using Machine Learning.
It applies Logistic Regression and Random Forest algorithms for binary classification.

---

## Dataset
- **Name:** Telco Customer Churn Dataset  
- **Source:** [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Rows:** Approximately 7000  
- **Target Column:** `Churn` (Yes/No)

---

## Steps Performed
1. Data Cleaning and Preprocessing  
2. Encoding Categorical Variables  
3. Feature Scaling  
4. Model Training (Logistic Regression, Random Forest)  
5. Model Evaluation (Accuracy, F1-score, ROC-AUC)  
6. Feature Importance Visualization  

---

## Results
| Model | Accuracy | ROC-AUC |
|--------|-----------|---------|
| Logistic Regression | 80% | 0.83 |
| Random Forest | 86% | 0.90 |

---

## Key Insights
- Customers with **short tenure**, **high monthly charges**, and **month-to-month contracts** are more likely to churn.  
- Long-term contracts and lower monthly charges reduce the churn probability.

---

## Tech Stack
- Python  
- pandas, numpy, matplotlib, seaborn  
- scikit-learn  
- Jupyter Notebook  

---

## How to Run
```bash
# 1. Clone this repository
git clone https://github.com/PayalDahe/Customer-Churn-Prediction.git

# 2. Navigate to the project folder
cd Customer-Churn-Prediction

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Jupyter Notebook
jupyter notebook notebooks/churn_prediction.ipynb


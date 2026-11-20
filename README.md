# 📊 Customer Churn Analysis and Prediction

Data Science Internship project at **Saiket Systems**.

## 📌 Project Overview

Customer churn means customers leaving a company's service. This project analyzes
churn in a telecom company, builds machine learning models to predict at-risk
customers, and recommends ways to improve customer retention.

## 📂 Dataset

- **Source:** Telco Customer Churn dataset
- **Size:** 7,043 customers and 21 columns
- **Target column:** `Churn` (Yes / No)
- **Overall churn rate:** 26.5% (1,869 customers)

## ✅ Tasks Completed

| Task | Description | Notebook |
|------|-------------|----------|
| 1 | Data Preparation | `Task1_Data_Preparation.ipynb` |
| 2 | Exploratory Data Analysis (EDA) | `Task2_EDA.ipynb` |
| 4 | Churn Prediction Model | `Task4_Churn_Prediction.ipynb` |
| 5 | Model Evaluation and Interpretation | `Task5_Model_Evaluation.ipynb` |
| 6 | Business Recommendations | `Task6_Business_Recommendations.ipynb` |

## 🔍 What I Did

**Task 1: Data Preparation**
- Loaded and explored the data
- Converted `TotalCharges` to numeric and handled 11 blank values
- Dropped `customerID` and encoded categorical variables
- Split the data into 80% training and 20% testing sets

**Task 2: Exploratory Data Analysis**
- Calculated and visualized the overall churn rate
- Analyzed customers by gender, partner and dependents
- Studied tenure, contract type and payment method against churn

**Task 4: Churn Prediction Model**
- Trained Logistic Regression, Decision Tree and Random Forest models
- Evaluated with accuracy, precision, recall and F1-score
- Tuned hyperparameters with GridSearchCV

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 0.806 |
| Decision Tree | 0.725 |
| Random Forest | 0.785 |

**Task 5: Model Evaluation and Interpretation**
- Evaluated the final model on the test set
- Plotted the ROC curve: **AUC = 0.84**
- Used feature importance to find the top churn drivers: tenure, total charges,
  monthly charges, fiber optic internet and contract type

**Task 6: Business Recommendations**
- Move month-to-month customers to longer contracts with incentives
- Encourage automatic payments instead of electronic check
- Run onboarding programs for new customers
- Promote tech support and online security add-ons
- Use model predictions to flag high-value customers at risk

## 💡 Key Insights

- Month-to-month customers churn at about **43%**, versus about **3%** on 2-year contracts
- Electronic check users churn more than customers on automatic payments
- Customers without tech support or online security churn far more
- Churned customers pay more per month than average, so losing them hurts revenue

## 💰 Estimated Business Impact

Churn costs about **$1.67 million per year** in lost revenue.

| Churners retained | Customers saved | New churn rate | Net yearly gain |
|-------------------|-----------------|----------------|-----------------|
| 10% | 187 | 23.9% | $150,261 |
| 20% | 374 | 21.2% | $300,523 |
| 30% | 561 | 18.6% | $450,784 |

> These are **estimates based on assumptions**: the retention offer costs 10% of
> the monthly bill, and the retention rates are scenarios, not predictions.

## 🛠 Tools

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Google Colab

## ▶️ How to Run

1. Download this repository
2. Open a notebook in Google Colab or Jupyter Notebook
3. Upload `Telco_Customer_Churn_Dataset.csv` next to it
4. Run all cells in order

## 👩‍💻 Author

**Jyoti Bhokare**, Data Science Intern at Saiket Systems


# End-to-End Customer Churn Prediction Using Machine Learning

<div align="center">
  <img src="https://github.com/waqi786/Customer-Churn-Prediction/blob/main/img.jpg" width="1000" alt="Churn Prediction">
</div>

---

## 🚀 Project Overview

This project is a **complete end-to-end machine learning pipeline** for predicting **customer churn**. It demonstrates how to transform raw customer data into actionable insights and deploy models that can predict whether a customer is likely to leave a company.  

This notebook covers:

- **Data Cleaning & Preprocessing**  
- **Exploratory Data Analysis (EDA)**  
- **Feature Engineering**  
- **Training Multiple Machine Learning Models**  
- **Evaluation with Accuracy, F1-Score, and ROC-AUC**  
- **Insights & Recommendations**  

---

## 📊 Dataset

- The dataset contains **7043 customers** and **21 features**, including demographics, subscription details, and payment information.
- Key columns:
  - `gender`, `SeniorCitizen`, `Partner`, `Dependents`
  - `tenure`, `PhoneService`, `InternetService`
  - `OnlineSecurity`, `DeviceProtection`, `TechSupport`
  - `Contract`, `PaperlessBilling`, `PaymentMethod`
  - `MonthlyCharges`, `TotalCharges`
  - `Churn` (Target column)

- **Source**: Publicly available customer churn dataset.

---

## 🧹 Data Preprocessing

- Missing values handled (`TotalCharges` column).  
- Categorical variables encoded using one-hot encoding.  
- Features and target separated:
  - Features: `X` (shape: 7043 x 30)  
  - Target: `y` (shape: 7043)  

- Train-test split:
  - Training set: 5634 samples  
  - Test set: 1409 samples  

---

## 🤖 Machine Learning Models Trained

The project includes **five different models** for comparison:

| Model                   | Accuracy | F1-score | ROC-AUC |
|-------------------------|----------|----------|---------|
| Logistic Regression      | 0.8055  | 0.6029  | 0.8420  |
| Gradient Boosting        | 0.7942  | 0.5672  | 0.8360  |
| XGBoost                  | 0.7821  | 0.5621  | 0.8166  |
| Random Forest            | 0.7921  | 0.5594  | 0.8259  |
| Decision Tree            | 0.7410  | 0.5020  | 0.6610  |

**Best Model**: Logistic Regression, based on overall accuracy and ROC-AUC.  

---

## 📈 Visualizations

The notebook contains **clear and attractive charts**:

- Count plots for categorical features  
- Correlation heatmaps  
- Distribution plots for numerical features  
- Churn rate comparisons across categories  

These visualizations help understand patterns in customer churn and provide actionable insights for business strategy.

---

## 🔧 Requirements

The project uses the following Python libraries:

```txt
pandas
numpy
matplotlib
seaborn
plotly
scikit-learn
xgboost
lightgbm
notebook
IPython

```
---

## Dataset Link: https://www.kaggle.com/datasets/mosapabdelghany/telcom-customer-churn-dataset

---

## 📝 How to Run

1. Clone the repository:
   
       git clone <your-repo-url>

3. Navigate to the project folder:
   
       cd customer-churn-prediction

5. Install dependencies:
   
       pip install -r requirements.txt

7. Open the Jupyter Notebook and run cells sequentially:
   
       jupyter notebook

---

## 💡 Insights & Recommendations

- Customers on month-to-month contracts are more likely to churn.

- Offering online security and tech support reduces churn.

- High monthly charges increase churn probability.

- Businesses can use this model to target retention strategies for at-risk customers.

---

## 👤 About the Author

WAQAR ALI — Data Science Student

I am passionate about Machine Learning, Predictive Analytics, and Business-Oriented Data Solutions.
This notebook demonstrates a complete end-to-end churn prediction system, designed with professional workflows and interpretable insights.

### Connect with me:

[📊 Kaggle](https://www.kaggle.com/waqi786)  
[💼 LinkedIn](https://www.linkedin.com/in/waqar-ali-a51297318)  
[🐙 GitHub](https://github.com/waqi786)  
[📘 Facebook](https://www.facebook.com/share/17eRzxaoQL/)


---

## 📌 Notebook created by Waqar Ali — 2025

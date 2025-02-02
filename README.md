# 📡 Telecom Customer Churn Prediction

## 📌 Project Overview:
This project applies **machine learning and data science techniques** to analyze customer churn in the telecom industry. Churn refers to customers discontinuing their services. By leveraging **predictive analytics, feature engineering, and model optimization**, we aim to help telecom companies proactively retain customers and optimize IT asset management strategies.

### 🔍 Key Goals:
- Identify factors influencing customer churn using **EDA and statistical analysis**.
- Build **predictive models (Random Forest, Decision Trees, KNN, and Logistic Regression)** to classify customers as potential churners or retainers.
- Optimize model performance using **hyperparameter tuning and feature selection**.
- Provide actionable insights to **minimize churn and enhance customer satisfaction**.

---

## 🗂️ Data Dictionary:

| Variable         | Description  |
|------------------|------------------------------------------------------------|
| CustomerID       | Unique customer identifier |
| Gender           | Customer's gender |
| SeniorCitizen    | Whether the customer is a senior citizen (1=Yes, 0=No) |
| Partner          | Whether the customer has a partner (Yes/No) |
| Dependents       | Whether the customer has dependents (Yes/No) |
| Tenure           | Number of months the customer has been with the company |
| PhoneService     | Whether the customer has phone service (Yes/No) |
| MultipleLines    | Whether the customer has multiple lines (Yes/No/No Phone Service) |
| InternetService  | Type of internet service (DSL/Fiber Optic/No) |
| OnlineSecurity   | Whether online security is enabled (Yes/No/No Internet Service) |
| OnlineBackup     | Whether online backup is enabled (Yes/No/No Internet Service) |
| DeviceProtection | Whether device protection is enabled (Yes/No/No Internet Service) |
| TechSupport      | Whether tech support is available (Yes/No/No Internet Service) |
| StreamingTV      | Whether streaming TV is included (Yes/No/No Internet Service) |
| StreamingMovies  | Whether streaming movies are included (Yes/No/No Internet Service) |
| Contract         | Type of contract (Month-to-Month/One Year/Two Years) |
| PaperlessBilling | Whether paperless billing is enabled (Yes/No) |
| PaymentMethod    | Payment method (Electronic Check, Mailed Check, Bank Transfer, Credit Card) |
| MonthlyCharges   | Monthly bill amount charged to the customer |
| TotalCharges     | Total amount charged to the customer |
| Churn            | Whether the customer churned (Yes/No) |

---

## 📊 Data Analysis & Insights:
### 🔎 Key Observations:
- **Contract type plays a major role in churn rates**: Customers with **month-to-month contracts churn more frequently** compared to those with annual or biennial contracts.
- **Higher monthly charges correlate with higher churn rates**, while long-tenure customers tend to stay.
- **Feature importance analysis** reveals that **tenure, total charges, and contract type** are the strongest predictors of churn.
- Customers using **fiber optic internet service** churn more compared to DSL users, possibly due to higher costs.

---

## 🤖 Machine Learning Models Used:
### 🔥 Model Selection & Performance:
| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| **Random Forest Classifier** | 82% | 80% | 78% | 79% |
| Decision Tree Classifier | 79% | 77% | 75% | 76% |
| K-Nearest Neighbors (KNN) | 76% | 73% | 70% | 72% |
| Logistic Regression | 74% | 71% | 69% | 70% |

### 🎯 Best Performing Model:
The **Random Forest Classifier (82% accuracy)** performed the best due to its ability to handle **imbalanced data, extract important features, and generalize well.**

#### 🚀 Model Optimization Steps:
- **Feature engineering:** Removed redundant variables, handled missing values, and transformed categorical features.
- **Hyperparameter tuning:** Used **GridSearchCV** to optimize parameters like `n_estimators`, `max_depth`, and `min_samples_split`.
- **Resampling techniques:** Applied **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the dataset and improve recall.

---

## 📢 Business Impact & IT Asset Management Relevance:
This project has significant implications for **IT Asset Management (ITAM) in telecom industries**:
✅ **Customer Retention:** Predictive insights allow telecom firms to **proactively address churn risks** by offering targeted discounts, loyalty programs, and service optimizations.
✅ **Optimized Resource Allocation:** Understanding churn behavior helps optimize **IT infrastructure, marketing strategies, and operational costs**.
✅ **Enhanced ITAM Strategies:** Efficient management of IT assets ensures **cost-effective service delivery and reduced revenue loss due to churn**.

---

## 🛠️ Tech Stack Used:
- **Programming:** Python 🐍
- **Data Processing:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, Random Forest, Decision Trees, KNN, Logistic Regression
- **Model Optimization:** GridSearchCV, SMOTE
- **Deployment:** Flask (for API integration) (optional)

---

## 📌 Conclusion:
This project highlights the **power of data science and machine learning in customer churn prediction.** By leveraging advanced ML techniques, we can help telecom companies **improve retention strategies, optimize IT assets, and enhance customer satisfaction.**

🔗 **GitHub:** [Akhileshwar-2509](https://github.com/Akhileshwar-2509)  
📂 **Dataset:** [Public Telecom Churn Dataset](https://github.com/Akhileshwar-2509/Telecom-Customer-Churn-Prediction/WA_Fn-UseC_-Telco-Customer-Churn.csv) 

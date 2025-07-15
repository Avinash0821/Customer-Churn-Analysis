## Telco Customer Churn Analysis (EDA Project)


# About the Project

This is an **EDA-based project** to investigate the reasons behind customer churn in a telco company. Using visualizations and statistical summaries, we uncover trends in demographics, service usage, and contractual behavior that influence churn.

---

# Business Objective

> To identify key customer segments that are at risk of leaving and uncover actionable insights that can help improve retention and reduce churn rates.

---

# Dataset Description

* **Source:** [Dataset on Telco Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
* **Rows:** 7,043
* **Columns:** 21
* **Target Variable:** `Churn` (Yes/No)

# Key Features:

* **Demographics:** `gender`, `SeniorCitizen`, `Partner`, `Dependents`
* **Account Info:** `tenure`, `Contract`, `MonthlyCharges`, `TotalCharges`
* **Services Signed Up:** `InternetService`, `OnlineSecurity`, `TechSupport`, etc.
* **Churn:** Binary indicator for customer leaving or staying.

---

# Exploratory Data Analysis

> Conducted using Python and Jupyter Notebook.

* Missing value treatment (especially `TotalCharges`)
* Data types and cleaning
* Univariate analysis of numerical and categorical variables
* Bivariate analysis with `Churn`
* Churn rate analysis by service types and demographics
* Correlation heatmap and tenure segmentation

📁 Notebook: [`Telco Churn Customer_EDA.ipynb`](https://github.com/Avinash0821/Customer-Churn-Analysis/blob/main/Main.ipynb)

---

# Key Insights

* Customers with **month-to-month contracts** and **fiber optic internet** show higher churn.
* **Senior citizens** and **those without online security/tech support** are more likely to churn.
* Customers with a **longer tenure** and **two-year contracts** tend to be more loyal.
* **High Monthly Charges** correlate with higher churn rates.

---

# Technologies Used

* **Languages:** Python
* **Libraries:** pandas, numpy, matplotlib, seaborn, plotly
* **Tools:** Jupyter Notebook, Git, GitHub

---

## ⚙️ How to Run

1. **Clone the Repository**

```
https://github.com/Avinash0821/Customer-Churn-Analysis
```

2. **Install Requirements**

   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**

   ```
   jupyter notebook Main.ipynb

   ```

---

# Results & Visualizations

Includes:

* Churn vs Tenure & Monthly Charges plots
* Contract type and churn distribution
* Count plots for services opted
* Heatmaps showing feature correlation


---

# Conclusion

The EDA revealed important behavioral patterns and demographic insights associated with customer churn. These insights can support data-driven strategies like targeted retention offers and improved customer support plans.

---

# Future Work

* Perform feature engineering for modeling
* Build a machine learning churn prediction model
* Develop an interactive dashboard using Streamlit or Power BI

---

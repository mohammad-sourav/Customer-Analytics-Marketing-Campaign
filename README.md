# Data-Driven Marketing Campaign Effectiveness: Identifying High-Response Customer Segments and Predicting Purchase Behavior

## Project Overview
This repository contains a comprehensive data science and customer analytics project designed to evaluate marketing campaign effectiveness, identify high-response customer segments, and predict customer purchase behavior. By leveraging advanced exploratory data analysis (EDA), statistical testing, and robust machine learning predictive modeling, this project empowers businesses to optimize marketing expenditure, enhance campaign ROI, and make data-driven strategic decisions.

---

## Repository Structure
```text
Customer-Analytics-Marketing-Campaign/
│
├── data/
│   ├── raw/                  # Original raw dataset (Dataset.csv)
│   └── preprocessed/         # Cleaned and processed dataset (cleaned_customer_data.xlsx)
│
├── notebooks/                # Jupyter notebooks containing step-by-step workflow
│   ├── 01_data_cleaning_and_validation.ipynb
│   ├── 02_eda_and_statistical_testing.ipynb
│   └── 03_predictive_modeling.ipynb
│
├── models/                   # Trained machine learning models (.joblib)
│   └── xgboost_campaign_model.joblib
│
├── outputs/                  # Generated figures, confusion matrices, and EDA plots
│   ├── feature_importance_xgboost.png
│   ├── confusion_matrix_logistic_regression.png
│   ├── confusion_matrix_random_forest.png
│   ├── confusion_matrix_xgboost.png
│   └── spending_vs_response_boxplot.png
│
├── requirements.txt          # Python dependencies required to run the project
└── .gitignore                # Git ignore configuration file

```
### Tech Stack & Libraries

* **Language:** Python
* **Environment:** Jupyter Notebook
* **Core Libraries:**
  * **Data Manipulation & Analysis:** Pandas, NumPy
  * **Machine Learning:** Scikit-Learn, XGBoost
  * **Data Visualization:** Matplotlib, Seaborn

---

### Key Workflow & Methodology

* **Data Cleaning & Validation:**
  Handled missing values, corrected data types, and filtered outliers to ensure high-quality data integrity.

* **Exploratory Data Analysis (EDA) & Statistical Testing:**
  Uncovered hidden customer behavioral patterns, analyzed feature correlations, and conducted statistical tests to segment high-response customer groups.

* **Predictive Modeling:**
  Trained and optimized classification models (including Logistic Regression, Random Forest, and XGBoost) to predict customer purchase response.

* **Model Evaluation & Insights:**
  Evaluated model performance using confusion matrices, classification metrics, and feature importance plots to determine key drivers of customer response.

---

### Key Insights & Findings

* Identified specific demographic and behavioral segments that yield the highest marketing campaign response rates.
* XGBoost demonstrated superior predictive performance in identifying potential buyers, significantly reducing false positives in campaign targeting.

---

### 👤 Author

**Mohammad Sourav**  
*Interdisciplinary Researcher | Consumer Psychology, Artificial Intelligence & Data Science*

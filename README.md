# Employee Attrition Prediction using Machine Learning

## 📌 Project Overview

Employee attrition is a major challenge for organizations because it increases recruitment costs, training expenses, and reduces overall productivity. This project develops a Machine Learning solution that predicts whether an employee is likely to leave the company based on HR-related factors such as job satisfaction, monthly income, overtime, work-life balance, and years at the company.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, model evaluation, feature importance analysis, and business recommendations for Human Resources (HR).

---

# 🎯 Objectives

* Analyze employee attrition patterns.
* Perform data cleaning and preprocessing.
* Build predictive machine learning models.
* Compare multiple classification algorithms.
* Identify the most important factors influencing employee attrition.
* Generate actionable HR insights and recommendations.

---

# 📊 Dataset Information

**Dataset Name:** IBM HR Analytics Employee Attrition Dataset

**Source:** Kaggle

**Total Records:** 1,470 Employees

**Total Features:** 35 Columns

**Target Variable:** Attrition (Yes / No)

---

# 🛠️ Technologies Used

* Python 3.x
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

# 🤖 Machine Learning Models

The following classification models were trained and evaluated:

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier

---

# 📈 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix
* Feature Importance Analysis

---

# 📂 Project Structure

```
EmployeeAttrition_Dhanush/
│
├── analysis.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── README.md
├── requirements.txt
├── summary.docx
│
├── charts/
│   ├── chart1_department_attrition.png
│   ├── chart2_jobrole_attrition.png
│   ├── chart3_income_boxplot.png
│   ├── chart4_worklife_balance.png
│   ├── chart5_years_company.png
│   ├── chart_confusion_matrix.png
│   ├── chart_feature_importance.png
│   └── chart_roc_curve.png
│
└── outputs/
    ├── model_metrics.csv
    └── feature_importance.csv
```

---

# 🚀 How to Run the Project

### 1. Clone or Download the Project

```bash
git clone <repository-url>
```

or download the ZIP file and extract it.

### 2. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 3. Open the Notebook

```bash
jupyter notebook
```

Open:

```
analysis.ipynb
```

Run all cells from top to bottom.

---

# 📊 Exploratory Data Analysis

The project includes:

* Employee Attrition Distribution
* Department-wise Attrition Analysis
* Job Role-wise Attrition Analysis
* Monthly Income vs Attrition
* Work-Life Balance Analysis
* Years at Company Analysis
* Correlation Heatmap

---

# 📈 Model Performance

Three machine learning models were trained and compared based on multiple evaluation metrics.

The comparison includes:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score

The best-performing model was selected based on its overall predictive performance and balanced classification capability.

---

# 💼 Business Insights

The analysis revealed several important findings:

* Employee attrition is influenced by multiple workplace factors rather than salary alone.
* Job Satisfaction, Overtime, Monthly Income, Years at Company, and Work-Life Balance significantly affect employee retention.
* Certain departments and job roles experience higher employee turnover.
* Machine Learning can assist HR teams in identifying employees who may be at risk of leaving and support proactive retention strategies.

---

# 🔮 Future Improvements

Possible enhancements include:

* Hyperparameter tuning for improved accuracy.
* Deployment using Streamlit or Flask.
* Integration with live HR databases.
* Real-time employee attrition monitoring dashboard.
* Advanced ensemble models such as XGBoost or LightGBM.

---

# 📚 Requirements

Install all required libraries using:

```bash
pip install -r requirements.txt
```

---

# 👨‍💻 Author

**Gundu Dhanush**

Machine Learning Internship Project

Week 2 – Employee Attrition Prediction

---

## 📄 License

This project is developed for educational and internship purposes only.

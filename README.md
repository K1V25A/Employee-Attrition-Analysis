# 👥 Employee Attrition Analysis

📌 Project Overview

Employee attrition is one of the biggest challenges faced by organizations, leading to increased recruitment costs, productivity loss, and reduced employee morale.

This project analyzes employee attrition data to identify the key factors influencing employee turnover and provides data-driven insights that can help organizations improve employee retention.

This project was completed as part of the **Business Analyst Internship at Slash Mark IT Solutions**.

 🎯 Business Problem

High employee attrition negatively impacts an organization's performance by increasing hiring costs, reducing productivity, and affecting team stability.

The objective of this project is to analyze employee data, identify the major reasons behind employee attrition, and provide actionable recommendations to support HR decision-making.

 🎯 Objectives

- Understand employee attrition patterns.
- Perform data cleaning and preprocessing.
- Explore relationships between employee characteristics and attrition.
- Identify important factors influencing employee turnover.
- Build predictive models to estimate attrition risk.
- Generate business insights for HR departments.

 📊 Dataset

The project uses the **IBM HR Analytics Employee Attrition & Performance Dataset**.

The dataset contains employee-related information such as:

- Age
- Attrition
- Business Travel
- Department
- Distance From Home
- Education
- Environment Satisfaction
- Gender
- Job Involvement
- Job Level
- Job Role
- Job Satisfaction
- Marital Status
- Monthly Income
- OverTime
- Performance Rating
- Stock Option Level
- Total Working Years
- Work-Life Balance
- Years at Company
- Years Since Last Promotion
- Years With Current Manager

🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SHAP (Explainable AI)
- SMOTE
- Grid Search

 🔄 Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Handling Class Imbalance using SMOTE
6. Model Training
7. Hyperparameter Tuning
8. Model Evaluation
9. SHAP Explainability
10. Business Insights & Recommendations

 📈 Exploratory Data Analysis

The project includes:

- Missing value analysis
- Distribution analysis
- Correlation analysis
- Attrition comparison across departments
- Overtime analysis
- Monthly income analysis
- Job satisfaction analysis
- Work-life balance analysis
- Feature importance visualization

 🤖 Machine Learning

Models were trained to predict employee attrition.

The workflow includes:

- Train-Test Split
- Data Scaling
- Feature Selection
- Model Training
- Hyperparameter Tuning using Grid Search
- Performance Evaluation

 📊 Model Evaluation

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

The project also uses **SHAP (SHapley Additive Explanations)** to understand how different features influence model predictions.

 💡 Key Business Insights

The analysis revealed several important findings:

- Employees working overtime were more likely to leave the organization.
- Lower monthly income was associated with higher attrition.
- Poor work-life balance increased employee turnover.
- Employees with fewer years at the company showed higher attrition rates.
- Certain departments and job roles experienced higher employee turnover than others.

 📌 Business Recommendations

Based on the analysis, organizations should consider:

- Reducing excessive overtime.
- Improving work-life balance initiatives.
- Reviewing compensation structures.
- Strengthening employee engagement programs.
- Providing career growth opportunities.
- Monitoring high-risk employees using predictive analytics.

 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/employee-attrition-analysis.git
```

2. Navigate to the project directory

```bash
cd employee-attrition-analysis
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Open Jupyter Notebook

```bash
jupyter notebook
```

5. Run all notebook cells.

 📂 Project Structure

```
Employee-Attrition-Analysis/
│
├── Data/
│   └── HR_Employee_Attrition.csv
│
├── Notebook/
│   └── Employee_Attrition_Analysis.ipynb
│
├── Images/
│   └── Charts
│
├── README.md
└── requirements.txt
```

 📈 Business Value

This project demonstrates how data analytics and machine learning can support Human Resource teams in identifying employees at risk of leaving the organization.

The insights generated can help organizations:

- Improve employee retention
- Reduce hiring costs
- Increase employee satisfaction
- Support strategic HR decision-making

 🔮 Future Improvements

- Deploy the predictive model using Streamlit.
- Build an interactive Power BI or Tableau dashboard.
- Integrate real-time employee data.
- Improve prediction accuracy using ensemble models.

 👩‍💻 Author

**Kavya**

B.E. Computer Science and Business Systems (CSBS)

Business Analytics | Data Analytics | SQL | Python | Tableau



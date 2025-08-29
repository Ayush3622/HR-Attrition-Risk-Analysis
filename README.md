**HR-Attrition-Risk-Analysis-and-Workforce-Segmentation**

📝 **Problem Statement**

A leading company faced challenges with high **employee turnover**, lacking a clear understanding of the root causes and an inability to **proactively identify at-risk individuals**.

Key questions addressed:

- **What are the key drivers of employee attrition?**
- **Which departments and job roles are most affected?**
- **Can we predict which employees are likely to leave?**
- **What are the distinct employee personas within the workforce?**

🛠️ **Tech Stack**

- **Storage/Querying:** SQLite
- **Analysis/Modeling:** Python (**Pandas, Scikit-learn, Imblearn, Optuna**)
- **Visualization:** **Matplotlib, Seaborn, Power BI**
- **Dataset:** **IBM HR Analytics Employee Attrition & Performance**

📂 **Workflow**
- **Data Cleaning & Feature Engineering** (Python, Pandas)
- **SQL EDA** (Attrition rates by demographics, departments, etc.)
- **Machine Learning & Model Optimization:**
  - **K-Means** (Employee Segmentation)
  - **Random Forest + SMOTE** (Attrition Prediction)
  - **Advanced Tuning:** A full workflow including Feature Selection and Decision Threshold Adjustment to maximize recall.
- **Interactive Dashboard** (Power BI, 5 pages: Overview, Deep Dive, Segments, and a Predictive Tool)

💡 **Dashboard Overview**

- **Executive Summary:** High-level KPIs like Headcount, Overall Attrition Rate, and Average Tenure.
- **Attrition Deep Dive:** Analysis of historical attrition drivers using statistical and AI-powered visuals.
- **Workforce Segmentation:** A detailed look at the 4 key employee personas discovered by the K-Means model, showing their size, characteristics, and risk levels.
- **Retention Intervention Tool:** A predictive, actionable list of current employees with the highest risk scores, allowing HR to focus their retention efforts effectively.

📑 **Detailed Results**

👉 For a full breakdown of the project, including key insights, model performance, and detailed dashboard snapshots, please see the accompanying PDF report.

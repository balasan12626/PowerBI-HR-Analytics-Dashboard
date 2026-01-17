# 📑 Project Report Summary: HR Analytics & Employee Attrition

## 1. Executive Summary
This report provides a comprehensive analysis of employee attrition utilizing the **IBM HR Analytics Employee Attrition & Performance dataset**. The primary objective is to identify key drivers of turnover and actionable insights to improve retention rates. The analysis leverages Power BI for visualization and statistical correlations found within the data.

## 2. Project Scope & Data Overview
-   **Dataset**: `WA_Fn-UseC_-HR-Employee-Attrition.csv`
-   **Total Records**: 1470 Employees
-   **Features Analyzed**: 35 (including Age, Department, Job Role, Monthly Income, Satisfaction Levels, etc.)
-   **Goal**: To build a dynamic dashboard that visualizes attrition trends and demographics.

## 3. Methodology
The project followed a structured data analysis pipeline:
1.  **Data Ingestion**: Loading the raw CSV data.
2.  **Data Cleaning**: Checking for missing values (none found) and consistent data types.
3.  **Data Modeling**: Creating relationships and calculating measures (e.g., Attrition Rate, Average Salary).
4.  **Visualization**: Developing interactive Power BI dashboards to display KPIs.

## 4. Key Findings & Insights

### 🔹 Attrition vs. Demographics
-   **Age Group**: Employees aged **25-35** show the highest attrition activity, potentially due to career exploration or higher mobility in early career stages.
-   **Gender**: Attrition rates are comparable between genders, though specific roles show variances.
-   **Marital Status**: **Single** employees have a significantly higher likelihood of leaving compared to Married or Divorced counterparts.

### 🔹 Job Role & Department Analysis
-   **High Turnover Roles**: **Sales Representatives** and **Laboratory Technicians** exhibit the highest attrition rates. This correlates with lower average monthly income and high travel frequency.
-   **Stable Roles**: **Manufacturing Directors** and **Research Directors** show very high retention, correlating with higher experience and compensation.
-   **Department**: The **Sales** department has the highest overall attrition percentage compared to R&D and HR.

### 🔹 Income & Satisfaction Correlation
-   **Income Factor**: There is a strong negative correlation between **Monthly Income** and Attrition. Employees in lower income brackets are more prone to leaving.
-   **Job Satisfaction**: Surprisingly, while low satisfaction (1-2) predicts some attrition, many employees with medium satisfaction (3) also leave, suggesting external factors (better offers) play a role.
-   **Overtime**: Employees working frequent **Overtime** have a markedly higher attrition rate (approx. 3x higher) than those who do not.

## 5. Strategic Recommendations

Based on the analysis, the following actions are recommended to mitigate attrition:

1.  **Compensation Review**: Conduct a market salary benchmark, especially for **Sales Representatives** and entry-level **R&D** roles, to ensure competitive pay.
2.  **Work-Life Balance Programs**: Since Overtime is a major predictor of turnover, investigate workload distribution and consider hiring additional support or implementing flex-time policies.
3.  **Career Development Pathways**: For the 25-35 age group, implement clearer career progression plans and mentorship programs to improve engagement and retention.
4.  **Targeted Retention Strategies**: Focus retention efforts on **Single** employees and high-risk job roles through engagement activities and personalized benefits.

## 6. Conclusion
The HR Analysis Dashboard successfully highlights critical areas of concern regarding employee turnover. By addressing the factors of Income, Overtime, and Role-specific challenges, the organization can expect to see a reduction in attrition rates and an improvement in overall employee satisfaction.

---
*Report generated based on project data and Power BI analysis findings.*

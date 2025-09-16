📊 HR Analytics Dashboard – Employee Performance & Attrition Analysis

This project focuses on understanding employee attrition (how many employees leave the company) and finding insights to improve retention & performance.

🔹 Steps Followed
1. Data Loading

 - Loaded the HR Analytics dataset (CSV file) into Power BI Query Editor.

 - Dataset had 38 columns with employee details such as age, department, education, salary, and attrition status.

2. Data Cleaning

 - Removed null values from the last column.

 - Applied auto-detect data type option to ensure every column had the correct format (date, text, number, etc.).

 - Verified that key columns like Age, Department, Salary, Attrition were correctly formatted.

3. Data Transformation

 - Created a new column AttritionCount:

   If employee attrition = “Yes” → 1

   If attrition = “No” → 0

 - Created a measure Attrition Rate = (Number of employees left ÷ Total employees).

 - These transformations helped to calculate attrition at different levels (by age, salary, department, etc.).

4. Data Analysis

 - Explored how attrition varies across different factors such as salary, age, education background, and years of service.

 - Compared attrition patterns between groups to identify pain points for HR.

5. Dashboard Creation

 - Built interactive visuals using Bar Charts, Donut Charts, and KPI Cards.

 - Dashboard highlights:

  1. Attrition by Age Group

  2. Attrition by Salary Slabs

  3. Attrition by Education Field

  4. Attrition by Years at Company

  5.Overall Attrition Rate & Employee Count


🔹 Key Insights

  1. Salary Factor

   Company’s average salary = 6.5k.

   163 employees earn below 5k, and most of them are leaving → salary dissatisfaction is a big driver of attrition.

  2. Education Background

   Employees from Life Sciences background leave most often.

   Likely due to lack of technical skills → Upskilling programs are needed.

  3. Age Group Impact

   Employees aged 26–35 show the highest attrition rate.

   HR should focus on understanding their challenges (work-life balance, career growth, etc.).

  4. Experience Level

   Freshers/new joiners leave the company at higher rates.

   Suggestion: Stronger onboarding, mentoring, and training programs are needed.


🔹 Impact of Dashboard

  - Helps HR identify root causes of employee attrition.

  - Provides actionable strategies to:

      Improve employee retention

      Enhance performance & job satisfaction

      Reduce attrition costs for the company

🔹 Tech Stack

  - Power BI (Data Cleaning, Transformation, Visualization)

  - HR Analytics Dataset (CSV)

  - MS-Excel

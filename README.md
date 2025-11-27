1. Short Description / Purpose

The Health Care Analytics Dashboard provides a unified view of patient data including gender, age group, smoking habits, weight status, heart attack risk, stroke probability, and health risk classification.
It helps hospitals and analysts track patient trends, highlight critical cases, and support targeted intervention strategies.

2. Tech Stack

This project was developed using the following tools and technologies:

Power BI Desktop – Interactive visualizations and dashboards

Power Query (M) – ETL cleanup (missing values, categorization, merging datasets)

DAX (Data Analysis Expressions) – Calculations for KPIs and health risk measures

SQL / Excel Dataset – Source patient health dataset

Data Modeling – Relationships between demographic and health metrics

Power BI Service – Publishing, sharing, and scheduled refresh

3. Data Source

Source: Patient health dataset (Excel/CSV).
The dataset contains:

Patient demographics (Age, Gender, Race)

Weight classification (Overweight, Not Overweight)

Smoking habits

Health risk categories (Normal, Moderate, High, Critical)

Heart attack & stroke indicators

Occupation & weight patterns

Data was cleaned in Power Query and aggregated using DAX for health metrics.

4. Features / Highlights
Business Problem

Hospitals needed a quick way to identify vulnerable patient groups and understand risk factors such as smoking, obesity, and age distribution.
Manual reports made it difficult to track critical cases or demographic trends.

5. Goal of the Dashboard

To build an analytics solution that:

Identifies patients at high or critical health risk

Shows distribution of heart attack and stroke cases

Analyzes smoking habits and weight by demographics

Helps medical teams focus on high-risk age groups

Visualizes population-level health insights for better planning

6. Top KPIs

Total Patients: 2166

Female Not Overweight: Count displayed dynamically by gender

Smoking Habit – High Health Risk: 478 patients

Critical Health Risk (<30 min): 22 patients

Demographic & Health Insights

% of Heart Attack (Pie Chart): Shows proportion of patients with heart attack history

% of Stroke (Pie Chart): Identifies stroke-affected patients

Count of Overweight by Race (Bar Chart): Chinese, Malay, Indian, and others comparison

Health Risk by Age Group (Bar Chart): Displays how risk changes by age (20–80+)

Health Category Distribution (Line Chart): Good, moderate, poor etc. trend

Count of Health Risk Levels (Bar Chart): Normal, moderate, high, critical

Average Weight by Occupation (Treemap): Highlights occupation-wise weight patterns

7. Filters Used

Gender Filter (Toggle): Male / Female

Health Risk Dropdown

Age Group Dropdown

These filters allow real-time slicing of data and multi-dimensional analysis.

8. Data Modeling

Built a clean data model with:

Patient Fact Table: healthRisk, heart attack, stroke, weight, lifestyle

Demographic Dimensions: age group, race, gender, occupation

Calculated Columns: BMI category, risk grouping

Measures: % heart attack, % stroke, count of high-risk patients, average weight

Optimized using:

Star-schema design

DAX measures instead of calculated columns where needed

Removing nulls & redundant columns

Business Impact & Insights

Identified 478 smokers with high health risk, assisting health teams in targeted interventions.

Highlighted critical-risk patients, enabling faster medical attention.

Agewise analysis improved prediction of high-risk age groups (50–60).

Race and occupation insights support community health initiatives.

Automated reporting reduced manual analysis time and improved decision-making accuracy.
9. ScreenShot
https://github.com/Mayuri-ai/HealthCare-Analytics/blob/main/HealthCareAnalytics_Dashboard.png

🏥 Hospital Management System Dashboard
📌 Overview

This project focuses on analyzing hospital data using SQL and Excel dashboards.
It helps to understand patient details, doctor performance, department analysis, and revenue insights in a simple and interactive way.

🛠️ Tools Used
SQL Server (SSMS)
Microsoft Excel (Dashboard Creation)
📂 Dataset Details

The dataset contains hospital-related information such as:

Patient ID, Name, Age, Gender
Doctor & Department
Diagnosis & Treatment
Admission Date & Discharge Date
Length of Stay
Bill Amount
🧠 SQL Analysis

SQL queries are used to extract meaningful insights:

Total Patients Count
Gender-wise Patient Distribution
Department-wise Patients
Doctor-wise Patient Count
Average Age of Patients
Total Revenue Calculation
Revenue by Department
Diagnosis-wise Patient Count
Monthly Patient Trends

Example:

SELECT COUNT(*) AS Total_Patients 
FROM [Hospital DB].[dbo].[HOSPITAL DATASET];

SELECT DEPARTMENT, COUNT(*) AS Total
FROM [Hospital DB].[dbo].[HOSPITAL DATASET]
GROUP BY DEPARTMENT;
📊 Dashboard Features
🔹 Filters Available
Month (Admission Date)
Department
Doctor
Diagnosis
Treatment
📌 Key Metrics
Total Patients
Average Length of Stay
Average Treatment Cost
Average Patient Age
📈 Visualizations
Patient Census (Monthly Patients)
Monthly Revenue Analysis
Gender Distribution
Patient Count by Treatment
Revenue by Treatment
Patient Count by Diagnosis
Revenue by Diagnosis
Patient per Doctor
Doctor Performance
Patient per Department
Revenue per Department
📸 Screenshots
SQL Queries Output

Dashboard - Home

Treatment Analysis

Diagnosis Analysis

Doctor Analysis

Department Analysis

🔍 Key Insights
Total patients count is clearly tracked across months.
Some departments generate higher revenue compared to others.
Certain diagnoses (like infections) have higher patient count.
Doctor-wise performance helps identify workload distribution.
Treatment types impact both patient count and revenue.
🎯 Conclusion

This project demonstrates how SQL and Excel dashboards can be used to analyze hospital data effectively and support better decision-making.<img width="1920" height="986" alt="major project home dashboard" src="https://github.com/user-attachments/assets/bcf21614-8bea-44f9-9c52-e40d91c88096" />
<img width="1920" height="986" alt="department dashboard" src="https://github.com/user-attachments/assets/b07d7d1d-15e2-471a-8db8-6aeb901969f5" />
<img width="1920" height="983" alt="mp doctor dashboard" src="https://github.com/user-attachments/assets/7cd45abb-4391-4f42-b913-4025aa0eb414" />
<img width="1920" height="1000" alt="Treatment dashboard" src="https://github.com/user-attachments/assets/356338b1-07d2-473a-b9f8-7782f2d8d04e" />
<img width="1920" height="1004" alt="treatment dashboard mp" src="https://github.com/user-attachments/assets/9154ba45-06e2-4c89-928e-2ad74ad891e5" />
<img width="1920" height="1007" alt="major project sql queries" src="https://github.com/user-attachments/assets/97213927-6dc6-426f-9599-3ec7f7c6441b" />
<img width="1920" height="1007" alt="sql queries pg 2" src="https://github.com/user-attachments/assets/111f06db-0275-429f-9a48-f9809c88abc1" />
<img width="1920" height="997" alt="sql queries pg3" src="https://github.com/user-attachments/assets/2f561240-8d1b-45cc-a236-24e81a467b69" />

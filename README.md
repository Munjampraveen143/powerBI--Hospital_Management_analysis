# 🏥 Hospital Management Analysis Dashboard (Power BI)

Welcome to my **Hospital Management Analysis Dashboard** project!  
This Power BI dashboard is designed to analyze hospital operations and patient data. It helps hospital management teams monitor **patient volume, billing, appointment fees, satisfaction scores, and demographics**.

The dashboard also provides **interactive filtering** for deep analysis by **Doctor, Department, and Date Range**.

---

# 🎯 Business Problems Solved

- Which department has the highest patient count?
- What is the total hospital revenue and appointment fee collection?
- Which departments have the best and lowest patient satisfaction?
- What is the gender distribution of patients?
- What is the race distribution of patients?
- How do patients vary by department and doctor?

---

# 📊 Dashboard KPIs

- **Total Patients:** 9K  
- **Total Bill:** 509M  
- **Appointment Fees:** 5M  

---

# 📈 Dashboard Visuals

- Number of Patients by Department  
- Avg Patient Satisfaction Score by Department  
- Gender Distribution of Patients  
- Number of Patients by Race  
- KPI Cards (Patients, Bill, Fees)  
- Doctor Name Slicer  
- Department Slicer  
- Date Range Filter  

---

# 🛠 Tools & Technologies Used

- Microsoft Power BI  
- Power Query (Cleaning & Transformation)  
- DAX (Measures & KPIs)  
- Data Modeling  
- Interactive Dashboard Design  

---

# 🗂 Dataset Information

The dataset contains hospital-related information such as:

- Patient details  
- Department information  
- Doctor names  
- Billing details  
- Appointment fees  
- Satisfaction scores  
- Gender and race categories  
- Date fields for timeline filtering  

---

# 🧠 DAX Measures Used

Below are sample DAX measures used in the dashboard:

### ✅ Total Patients
```DAX
Total Patients = COUNT(Hospital[Patient_ID])
✅ Total Bill
Total Bill = SUM(Hospital[Bill_Amount])
✅ Appointment Fees
Appointment Fees = SUM(Hospital[Appointment_Fee])
✅ Average Satisfaction Score
Avg Satisfaction Score = AVERAGE(Hospital[Satisfaction_Score])
✅ Patients by Department
Patients by Department = COUNT(Hospital[Patient_ID])
📅 Date Range
This dashboard supports analysis between:

01-04-2019 to 30-10-2020

📷 Dashboard Preview
Upload your dashboard screenshot to the repository and add:

![Dashboard Preview](./dashboard.png)
📂 Project Structure
Hospital-Management-Analysis/
│
├── Hospital_Management_Analysis.pbix
├── dashboard.png
└── README.md

🚀 How to Use This Project
Download the .pbix file from this repository

Open it using Power BI Desktop

Explore the report using slicers and visuals

📌 Key Learnings
Created KPI metrics using DAX

Built interactive filters for dynamic analysis

Designed a clean and structured dashboard layout

Applied data modeling concepts in Power BI

⭐ If you find this project useful, don’t forget to star the repository!


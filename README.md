# 🏥 Hospital Data Analysis Using SQL |

This repository contains structured SQL queries that explore hospital performance, patient demographics, medical expenses, and departmental efficiency. The project simulates a real-world healthcare database and was completed as part of the **30 Days SQL Micro Course Certificate Assignment**.

---

### 🧾 Project Overview

The dataset is stored in a SQL Server database under `[Hospital].[dbo].[Hospital_Data]`, featuring fields such as:

- `Hospital_Name`
- `Department`
- `Patients_Count`
- `Doctors_Count`
- `Medical_Expenses`
- `Location`
- `Admission_Date`
- `Discharge_Date`

Each query answers a specific business question relevant to hospital management, resource planning, and patient care analysis.

---

### 🔍 Key SQL Queries & Business Questions

| # | Question                                                                 | Technique Used          |
|---|--------------------------------------------------------------------------|--------------------------|
| 1 | Total number of patients per hospital                                    | `SUM`, `GROUP BY`        |
| 2 | Average number of doctors per hospital                                   | `AVG`, `GROUP BY`        |
| 3 | Top 3 departments with highest patient count                             | `TOP`, `SUM`, `ORDER BY` |
| 4 | Hospital with maximum medical expenses                                   | `TOP 1`, `SUM`, `ORDER BY DESC` |
| 5 | Daily average medical expenses per hospital                              | `DATEDIFF`, `AVG`, Calculated field |
| 6 | Patient with longest hospital stay                                       | `DATEDIFF`, `ORDER BY DESC` |
| 7 | Total patients treated per city                                          | `GROUP BY Location`, `SUM` |
| 8 | Average length of stay per department                                    | `AVG(DATEDIFF)`, multi-level `GROUP BY` |
| 9 | Department with the lowest number of patients                            | `TOP 1`, `ORDER BY ASC` |
| 10| Monthly medical expenses report (formatted by year and month)           | `FORMAT()`, `GROUP BY`, `ORDER BY` |

---

### 💼 Skills Demonstrated

- 📌 Advanced SQL functions: `DATEDIFF`, `FORMAT`, `AVG`, `SUM`, `TOP`
- 🧠 Time-based analysis using dates and duration calculations
- 📊 Performance ranking and efficiency metrics
- 🏥 Healthcare-centric data modeling and aggregation
- 🧾 Report generation suitable for executive dashboards

---

### 📂 Repository Structure

- `Hospital_SQL_Assignment.sql` — Contains all solution queries
- `README.md` — Overview, objectives, and explanation of each analysis
- `Hospital_SQL.docx` — Original assignment document (if included)
- `Screenshots/` *(optional)* — Visual outputs or query results

---

### 🧠 Business Impact

These queries simulate reports used by hospital administrators to:
- Track resource allocation (doctors, departments)
- Manage patient load and length of stay
- Identify cost drivers and revenue leakage
- Improve department-level performance
- Generate month-wise financial summaries

This is an ideal case study for roles in **Healthcare Analytics**, **BI Development**, and **SQL Reporting**.

---

### 🙋‍♀️ About Me

I'm **Surbhi**, a Data Analyst with a passion for clean insights and operational efficiency.  
I specialize in building dashboards, automating reports, and digging into data using SQL, Power BI, Excel, and Python.

📬 [LinkedIn](www.linkedin.com/in/surbhi-995926161)  
🌐 [GitHub Portfolio](https://github.com/surbhigzb98)

---

### ✅ How to Use

1. Clone the repository  
2. Open the `.sql` file in SSMS or any compatible SQL editor  
3. Connect to or simulate the `[Hospital_Data]` table  
4. Run queries individually to explore results  
5. Use the insights for interview prep or portfolio enhancement

---

Thanks for stopping by!  
Feel free to ⭐ the repo or drop feedback. Healthcare data deserves clarity and care 🌿📈

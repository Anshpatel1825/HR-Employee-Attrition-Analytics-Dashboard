# 📊 HR Employee Attrition Analytics Dashboard

## 📌 Project Overview

This project analyzes **employee attrition trends** using **Excel, SQL, and Power BI**.

The goal of this project is to understand:

- Why employees leave the company
- Which departments have higher attrition
- Which employees are at high risk of leaving
- How salary, experience, and promotion affect employee attrition

The dataset contains **10,000 employee records**.  
The project transforms raw HR data into **business insights and an interactive dashboard**.

---

# 🎯 Project Objectives

- Analyze employee attrition patterns
- Identify high-risk employees
- Study workforce distribution across departments
- Analyze salary and experience impact on attrition
- Build an interactive HR analytics dashboard

---

# 🗂 Dataset Information

Total Records: **10,000 Employees**

Important Columns:

- Employee_ID
- Age
- Gender
- Department
- Job_Role
- Monthly_Income
- Years_at_Company
- Attrition
- Distance_From_Home
- Work_Environment_Satisfaction

Additional columns were created for better analysis.

---

# 🧹 Step 1: Data Preparation (Excel)

Excel was used for **data cleaning and feature engineering**.

### Tasks Performed

- Checked missing values
- Verified duplicate records
- Standardized data format
- Created analytical columns

---

## New Columns Created

### 1️⃣ Income Category

Employees grouped based on salary.

| Income Range | Category |
|--------------|---------|
Below 5000 | Low |
5000–10000 | Medium |
Above 10000 | High |

Purpose:  
To analyze attrition across salary levels.

---

### 2️⃣ Experience Level

Employees grouped based on years in the company.

| Years | Level |
|------|------|
0–5 | Junior |
6–12 | Mid |
13+ | Senior |

Purpose:  
To analyze attrition across experience levels.

---

### 3️⃣ Promotion Status

Employees categorized based on promotion history.

| Condition | Status |
|----------|--------|
Recently promoted | Recently Promoted |
No promotion for 5+ years | No Promotion 5+ Years |

Purpose:  
To study promotion impact on attrition.

---

### 4️⃣ Risk Flag

Employees classified into risk groups.

| Risk | Meaning |
|------|--------|
Normal | Low attrition risk |
High Risk | Higher chance of leaving |

Purpose:  
Helps HR identify employees who may leave the company.

---

# 💾 Step 2: Data Analysis (SQL)

SQL was used for **data exploration and analysis**.

---

## Data Validation

Total Employees:

10,000

Duplicate Records:

No duplicate records found.

Missing Values:

No missing values found.

This confirms the dataset is **clean and reliable for analysis**.

---

# 📊 Key SQL Insights

## 1️⃣ Employee Attrition

Employees Stayed: **8003**

Employees Left: **1997**

Attrition Rate: **19.97%**

📌 Insight

Almost **1 out of every 5 employees leaves the company**.

---

## 2️⃣ Income Category Distribution

| Income Category | Employees |
|----------------|----------|
Medium | 5871 |
High | 2908 |
Low | 1221 |

📌 Insight

Most employees belong to the **medium income category**.

---

## 3️⃣ Attrition by Income

| Income Category | Attrition |
|----------------|----------|
Medium | 1176 |
High | 587 |
Low | 234 |

📌 Insight

Employees in the **medium income group show the highest attrition**.

---

## 4️⃣ Experience Level Distribution

| Experience Level | Employees |
|-----------------|-----------|
Senior | 7194 |
Mid | 1771 |
Junior | 1035 |

📌 Insight

The majority of employees are **senior-level employees**.

---

## 5️⃣ Attrition by Experience

| Experience Level | Attrition |
|-----------------|-----------|
Senior | 1438 |
Mid | 359 |
Junior | 200 |

📌 Insight

Senior employees contribute to the **largest share of attrition**.

---

## 6️⃣ Promotion Analysis

| Promotion Status | Employees |
|-----------------|-----------|
Recently Promoted | 5020 |
No Promotion 5+ Years | 4980 |

Attrition:

| Promotion Status | Attrition |
|-----------------|-----------|
Recently Promoted | 1021 |
No Promotion 5+ Years | 976 |

📌 Insight

Promotion distribution is **almost balanced across employees**.

---

## 7️⃣ Risk Analysis

| Risk Flag | Employees |
|-----------|----------|
Normal | 9440 |
High Risk | 560 |

📌 Insight

About **5.6% of employees are high-risk employees**.

---

## 8️⃣ Department Attrition

| Department | Attrition |
|-----------|----------|
Finance | 415 |
Marketing | 413 |
Sales | 398 |
IT | 390 |
HR | 381 |

📌 Insight

Attrition is **fairly balanced across departments**.

---

# 📈 Step 3: Power BI Dashboard

Power BI was used to create an **interactive HR analytics dashboard**.

---

# 📊 Dashboard Overview

![Dashboard](https://github.com/Anshpatel1825/HR-Employee-Attrition-Analytics-Dashboard/blob/main/Dashboard%20(1).png?raw=true)

[!Employee details](https://github.com/Anshpatel1825/HR-Employee-Attrition-Analytics-Dashboard/blob/main/Second%20Page.png?raw=true)
The dashboard provides a **complete overview of workforce performance and attrition trends**.

Main dashboard features include:

- KPI summary cards
- Income category analysis
- Job role distribution
- Department attrition analysis
- Promotion impact analysis
- Experience vs attrition comparison
- Risk flag monitoring
- Interactive filters
- Multi-page navigation
- Employee-level detailed table

---

# 📊 Dashboard KPIs

| Metric | Value |
|------|------|
Total Employees | 10,000 |
Total Attrition | 1,997 |
Attrition Rate | 19.97% |
High Risk Employees | 560 |

---

# 📊 Dashboard Insights

### Workforce Distribution

Most employees belong to the **medium salary group and senior experience level**.

---

### Attrition Trend

The company shows a **19.97% attrition rate**, indicating potential retention challenges.

---

### Department Analysis

Attrition occurs across all departments, with **Finance and Marketing slightly higher**.

---

### Risk Monitoring

Around **560 employees are classified as high risk**, allowing HR teams to take proactive action.

---

### Promotion Impact

Promotion distribution is balanced, suggesting **other factors may influence employee attrition**.

---

# ⚡ Dashboard Features

The dashboard includes:

- Interactive filters (Department, Gender, Experience Level, Income Category)
- Dynamic KPI cards
- Drill-through navigation to employee details
- Multi-page dashboard structure
- Interactive charts

These features allow HR teams to **quickly explore workforce data and make informed decisions**.

---

# 🛠 Tools Used

| Tool | Purpose |
|-----|--------|
Excel | Data cleaning and feature engineering |
SQL | Data exploration and analysis |
Power BI | Interactive dashboard creation |

---

# 🎯 Business Value

This project helps HR teams:

- Identify high-risk employees
- Understand attrition patterns
- Monitor department performance
- Improve employee retention strategies

---

# 📌 Conclusion

This project demonstrates how **data analytics can help organizations understand employee attrition trends**.

By combining **Excel, SQL, and Power BI**, raw HR data was transformed into **meaningful insights and an interactive dashboard** that supports **data-driven HR decisions**.

---

# 👨‍💻 Author

**Ansh Patel**

Data Analyst Portfolio Project

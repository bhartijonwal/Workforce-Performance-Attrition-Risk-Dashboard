# Workforce-Performance-Attrition-Risk-Dashboard

An interactive **Excel-based HR analytics dashboard** that helps identify attrition drivers, evaluate workforce performance trends, and flag employees with elevated retention risk.

---

## Project Overview

This project analyzes employee attrition patterns and workforce health using structured Excel analytics. It combines KPI tracking, pivot-based exploration, and a simple risk model so HR teams can make faster, evidence-based decisions.

The dashboard focuses on:
- Attrition trends by **experience band**, **income level**, and **department**
- Workforce quality indicators such as **average salary** and **job satisfaction**
- A rule-based **high-risk employee classification** for retention planning

---

## Key KPIs


- Total Attrition : 237 employees 
- Attrition Rate : 16.12% 
- Average Salary : ₹ 6,502.93 
- Average Job Satisfaction : 2.68 
- High-Risk Employees : 1181 


---

## Dashboard Highlights

### 1) Attrition by Experience
- Segments: **0–3 years**, **3–7 years**, **7+ years**
- Highest turnover appears in the **0–3 years** group, signaling early-tenure churn.

### 2) Attrition by Income Level
- Segments: **Low**, **Medium**, **High** income
- Attrition is strongest in lower-income bands, showing compensation-linked retention risk.

### 3) Attrition by Department
- Departments: **Human Resources**, **Research & Development**, **Sales**
- **Research & Development** shows the highest attrition, followed by Sales.

### 4) Risk Category Distribution
- Employees are labeled using a score derived from:
  - Job Satisfaction
  - Years at Company
  - Monthly Income
- Risk classes: **High Risk** and **Low Risk**

---

## How the Risk Logic Works (Concept)

A practical, rules-driven model assigns points based on risk factors:
- Lower satisfaction → higher risk points
- Lower tenure → higher risk points
- Lower monthly income → higher risk points

The total score is then mapped to a final risk category. This supports targeted retention outreach and prioritization.

---

## Tools & Techniques Used

- **Microsoft Excel**
- Excel Tables for structured data
- Pivot Tables and Pivot Charts for aggregations and visuals
- Slicers for interactive filtering (e.g., Department, Job Role)
- IF-based formulas for risk scoring and categorization
- Dashboard design and formatting best practices

---

## Business Insights

- Early-career employees are more likely to exit.
- Compensation is strongly associated with attrition.
- R&D requires focused retention intervention.
- A meaningful share of the workforce falls into high-risk class.

These insights can inform hiring plans, compensation reviews, and manager-level retention actions.

---

## Repository Contents

- `README.md` → Project documentation
- `ATTRITITION REPORT.docx` → Full project report
- `Screenshot 2026-02-28 224846.png` → Dashboard preview

---

## Dashboard Preview
https://github.com/bhartijonwal/Workforce-Performance-Attrition-Risk-Dashboard/blob/main/Screenshot%202026-02-28%20224846.png

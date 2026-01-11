# HR Attrition Analytics Dashboard (Power BI)

## 📌 Project Overview
This project analyzes employee attrition using Power BI to identify high-risk groups and key drivers of workforce turnover.  
The dashboard is designed to support HR and management teams in making data-driven retention decisions.

## 🎯 Objectives
- Measure overall attrition rate and workforce stability
- Identify departments, experience levels, income bands, and overtime patterns with high attrition risk
- Distinguish between attrition **volume** and **risk** using counts and rates appropriately
- Present insights through an executive overview and a detailed deep-dive analysis

## 📊 Dashboard Structure
### Page 1 – HR Attrition Overview
- Total Employees, Attrition Count, Attrition Rate
- Attrition Rate by Department
- Attrition Rate by Experience Group
- Attrition Rate by Income Band
- Attrition Rate by Overtime Status

### Page 2 – Attrition Deep Dive
- Top 5 Job Roles with Highest Attrition (Count)
- Attrition Risk by Experience Group (Rate)
- Attrition Rate by Income Band
- Key insights summarizing major findings

## 🧹 Data Preparation
- Raw HR dataset used without manual modification
- Data cleaning and transformation performed in Power Query
- Created derived fields:
  - Experience Group
  - Income Band
- DAX measures created for:
  - Attrition Count
  - Attrition Rate (%)
  - Average tenure and income

## 📁 Dataset
Source: IBM HR Analytics Attrition Dataset  
File: `HR-Employee-Attrition.csv`

## 🛠 Tools Used
- Power BI Desktop
- Power Query
- DAX
- GitHub

## 🔍 Key Insights
- Early-career employees (0–2 years) have the highest attrition risk
- Employees working overtime show significantly higher attrition
- Sales-related roles contribute the highest attrition volume
- Lower income bands experience higher attrition rates

## 📷 Dashboard Preview
<img width="969" height="548" alt="Screenshot 2026-01-06 232154" src="https://github.com/user-attachments/assets/4b32ef07-4db9-42b3-8353-1eb48cbe0f66" />

<img width="969" height="551" alt="Screenshot 2026-01-06 232223" src="https://github.com/user-attachments/assets/9757fac4-e777-4afe-a89e-4381c371c307" />


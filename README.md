# Employee Attrition Analysis (Python)

## Overview
This project analyzes employee attrition patterns in an HR dataset (4,504 records, 20 variables) to identify key drivers of employee turnover and propose data-backed retention strategies.

## Objectives
- Identify primary drivers of attrition (e.g., business travel, promotion gaps, role-specific turnover)
- Explore relationships between compensation, tenure, and attrition
- Translate insights into actionable HR recommendations

## Dataset
The dataset includes demographic, job, compensation, and career progression features such as:
Age, Gender, Department, Job Role, Job Level, Monthly Income, Business Travel, YearsAtCompany, YearsSinceLastPromotion, etc.

## Methods
- Data preprocessing: missing value treatment, duplicate handling
- Exploratory Data Analysis (EDA)
- Visualizations: distributions, boxplots, attrition breakdown, correlation heatmap, attrition by role

## Key Insights
- Attrition is higher among frequent business travelers
- Salary/job level trends do not fully explain attrition alone
- Longer gaps since last promotion are associated with higher attrition
- Certain roles (e.g., Sales / Research) show higher turnover patterns

## Business Recommendations
- Structured salary growth tied to skills/performance
- Targeted retention programs for frequent travelers
- Career roadmap + promotion cadence (e.g., review cycles, mentorship, fast-track paths)
- Role-specific retention initiatives for high-attrition functions

## Files
- Notebook: `notebooks/CIA4_MARIA_2428714.ipynb`
- Report: `reports/Employee_attrition_report.pdf`

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook

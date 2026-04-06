# Data Jobs Dashboard – Power BI Project

This project analyzes the 2024 data job market using Power BI, focusing on roles, salaries, hiring trends, and required skills.

The goal is to transform raw job posting data into an interactive dashboard that provides clear and actionable insights for job seekers and analysts.

---

## Project Overview

The dashboard explores:

- Job demand across different roles  
- Salary trends by position and location  
- Required skills in the data job market  
- Monthly hiring patterns  

This project demonstrates an end-to-end data analytics workflow, including data transformation, modeling, and visualization.

---

## Dashboard

### Data Jobs Dashboard
File:  
`Data jobs v1\Data_Jobs_Dashboard.pbix`

Features:
- Interactive filtering and slicers  
- Drill-through analysis  
- Market overview of data roles  

---

### Data Jobs Dashboard 2.0
File:  
`Data jobs v2\Data_Jobs_Dashboard_2.0.pbix`

Improvements:
- Optimized data model (star schema)  
- More efficient DAX measures  
- Cleaner and more focused layout  

---

## Data

The dataset is based on real-world 2024 job postings.

Files used:

- `job_postings_flat.csv` → initial dataset  
- `job_postings_monthly.xlsx` → time-based analysis  
- `star_schema_files/` → structured model for performance optimization  

---

## Process

### 1. Data Preparation
- Cleaned and transformed data using Power Query  
- Handled missing values and inconsistencies  
- Combined multiple files into a unified dataset  

### 2. Data Modeling
- Built relationships between tables  
- Designed a star schema for better performance  
- Created fact and dimension tables  

### 3. Analysis (DAX)
- Created measures for:
  - Total job postings  
  - Average salaries  
  - Role-based comparisons  
- Used measures instead of calculated columns for better performance  

### 4. Visualization
- Designed interactive dashboards  
- Applied filters, slicers, and drill-through  
- Focused on clarity and usability  

---

## Key Insights

- Data-related roles show strong demand across multiple regions  
- Salary varies significantly by role and specialization  
- Certain skills consistently appear across high-paying jobs  
- Hiring trends fluctuate across months  

---

## Tools Used

- Power BI  
- Power Query  
- DAX  
- Excel / CSV  

---

## How to Use

1. Download the `.pbix` files  
2. Open in Power BI Desktop  
3. Update data source paths if needed  
4. Explore the dashboard using filters and interactions  

---

## Notes

Some large files are not included due to GitHub size limits.

# Data Jobs Dashboard – Power BI Project (2 Reports)

> **An interactive analytics project exploring the global data job market using two complementary Power BI reports.**

This project analyzes 2024 data job postings to uncover insights about **salary trends, job demand, hiring platforms, and required skills**. Using Power BI, the project delivers two dashboards designed for different analytical needs: a **detailed multi-page analysis** and a **high-level executive summary**.

Together, these reports provide a clear view of how the modern data job market is evolving.

---

## Introduction

The data job market is vast and fragmented across multiple platforms, making it difficult to understand trends in roles, compensation, and required skills.

This project consolidates real-world job posting data and presents it through **interactive Power BI dashboards** designed for:

- Job Seekers  
- Career Switchers  
- Data Professionals  
- Hiring Analysts  

Using a dataset of global **2024 data job postings** (including job titles, salaries, skills, locations, and job types), the project delivers two reports tailored for different exploration styles:

- **Report 1: Multi-Page Deep-Dive Report** – Detailed exploration of market trends and role-specific insights.
- **Report 2: Single-Page Executive Summary** – High-level insights designed for quick understanding.

---

## Dashboard Files

- `Data_Jobs_Dashboard.pbix` – Report 1 (Two Pages)  
- `Data_Jobs_Dashboard_2.0.pbix` – Report 2 (One Page)

---

## Dataset

The analysis in this project is based on a single consolidated dataset:

`job_postings_flat (1)`

This dataset contains global job postings for data-related roles collected during 2024. Each row represents a single job listing and includes detailed information about the role, compensation, company, and required skills.

The dataset provides a comprehensive view of the data job market across different countries and platforms.

### Key Data Fields

The dataset includes attributes such as:

- **job_id** – Unique identifier for each job posting  
- **job_title** – Full job title from the posting  
- **job_title_short** – Standardized job title used for analysis (e.g., Data Analyst, Data Scientist)  
- **company_name** – Name of the hiring company  
- **job_location** – City or location of the job  
- **job_country** – Country where the job is based  
- **job_platform** – Platform where the job was posted (LinkedIn, Indeed, etc.)  
- **job_schedule_type** – Type of employment (full-time, contract, internship, etc.)

### Compensation Data

Salary-related columns provide insight into compensation across roles:

- **salary_year_avg** – Average yearly salary for the job posting  
- **salary_hour_avg** – Average hourly salary where available  

These fields allow comparisons of compensation across job titles and regions.

### Job Characteristics

Additional fields describe important job attributes:

- **work_from_home** – Indicates whether the role allows remote or hybrid work  
- **health_insurance** – Indicates whether health benefits are mentioned in the posting  
- **no_degree_mention** – Indicates if a degree requirement is not explicitly stated  
- **job_posted_date** – Date when the job was posted  

### Skills Information

The dataset also includes skills mentioned in job postings, enabling analysis of the most in-demand technical skills across roles.

### Dataset Purpose

This dataset enables analysis of:

- demand for different data-related roles  
- salary benchmarks across the industry  
- remote work trends  
- hiring platforms used by companies  
- technical skills most frequently requested by employers  

---

## Report 1: Multi-Page Market Deep Dive

### Overview

This two-page dashboard provides both a **high-level overview of the data job market** and a **detailed drill-through analysis for individual job titles**. It is designed for users who want deeper insights into salary patterns, role demand, and job characteristics.

---

### Page 1: High-Level Market Overview

This page presents a summary of the overall data job market, highlighting key KPIs and market trends.

**Insights Provided**

- **Job Count** – Total number of job postings analyzed (~479K)  
- **Average Job Rating** – Aggregated rating derived from available review data  
- **Median Yearly & Hourly Salary** – Compensation benchmarks across roles  
- **Jobs Over Time** – Monthly demand trends across 2024  
- **Job Title Popularity** – Most frequently posted data roles  
- **Hourly vs Median Salary Comparison** – Comparison between compensation models  
- **Job Statistics Table** – Interactive breakdown of job titles, salaries, counts, and trends  

---

### Page 2: Job Title Drill Through

This page allows users to drill down into **detailed insights for a selected job role** (for example, Data Analyst or Data Scientist).

**Insights Provided**

- Salary distribution (minimum, median, maximum)  
- Work From Home percentage  
- Jobs without degree requirements  
- Health insurance mentions  
- Global job distribution  
- Job platforms used for postings  
- Job schedule types (full-time, contract, internship, etc.)

---

### Key Features Used

- Power Query ETL for data transformation  
- DAX measures for key metrics  
- Interactive visuals with slicers and filters  
- Drill-through navigation  
- Map visuals and comparative charts  
- KPI cards and trend visualizations  

---

## Report 2: Single-Page Executive Dashboard (Version 2.0)

### Overview

This one-page dashboard focuses on **quick, high-level insights** into the data job market.

**Insights Provided**

- Job Count – Total number of analyzed job listings (~479K)  
- Skills Per Job – Average number of skills required per role (~4.8)  
- Median Salary (Yearly & Hourly) – Market-wide salary benchmarks  
- Skill Popularity – Most in-demand technical skills (Python, SQL, etc.)  
- Job Salary Comparison – Salary comparison across different roles  
- Interactive Filters – Filter insights by Job Title and Country  

This dashboard is designed for **fast exploration and executive-level insights**.

---

### Key Features Used

- One-page analytical layout  
- Interactive slicers for filtering  
- Skill demand analysis  
- Salary comparisons across job roles  

---

## Why This Project?

The two dashboards complement each other:

- **Report 1** – Detailed exploration and role-level insights  
- **Report 2** – Quick market summary and executive insights  

Together they provide a **complete analytical view of the 2024 data job market**.

---

## Skills Demonstrated

- Data transformation using Power Query  
- Analytical calculations using DAX  
- Interactive dashboard design  
- Visual storytelling with Power BI  
- Drill-through navigation and dynamic filtering  

---

## Contact

For feedback or collaboration:

[LinkedIn](https://www.linkedin.com/in/kartik-bhatia-a82718b7/)

---

## Included Files

- `Data_Jobs_Dashboard.pbix` – Multi-page analytical dashboard  
- `Data_Jobs_Dashboard_2.0.pbix` – Single-page executive dashboard  
- `README.md` – Project documentation

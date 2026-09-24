# 📊 UK Data Analyst Job Market Analysis (2026)

### Data Relational Modeling, SQL Querying, and Interactive Tableau Visualization

This end-to-end data analysis project explores current job market demand, key technical skill requirements, work arrangements, hiring industries, and geographic distribution for data roles across the UK. 

The data architecture was transformed from raw datasets into a **3rd Normal Form (3NF) relational database model** in PostgreSQL (Supabase), queried for key business insights, and visualized using **Tableau Public**.

---

## 📸 Dashboard Preview
<img width="291" height="368" alt="image" src="https://github.com/user-attachments/assets/a52e13f3-88da-4127-a54c-69c2fd2e41dc" />

> 🔗 **[Click Here to View the Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/alexleigh.thomas/viz/UK_Data_Analyst_Market_Analysis/Dashboard1?publish=yes)**

## 🛠️ Core Skills & Tech Stack Demonstrated

### 🗄️ Relational Database & Data Architecture (Supabase / PostgreSQL)
* ⭐ **3rd Normal Form (3NF) Design:** Schema normalized across core entity tables: `jobs`, `skills`, `job_skills` (junction table), `work_modes`, `job_categories`, `locations`, and `industries`.
* ⭐ **DDL Implementation:** Primary keys, foreign key constraints, and relational integrity enforced in PostgreSQL.
* ⭐ **Data Ingestion:** Clean CSV data pipelines imported respecting relational key order.

### 🔍 Advanced SQL Analysis & Querying
* ⭐ Built relational multi-table `JOIN` queries to analyze job market trends.
* ⭐ Evaluated skill frequencies grouped by job category while excluding soft skill categories.
* ⭐ Aggregated work arrangement patterns (`Hybrid`, `Onsite`, `Remote`) and sector distribution across UK postings.

### 📈 Data Visualization & Analytics (Tableau Public)
* ⭐ Designed a 4-quadrant executive dashboard balancing distinct analytical dimensions.
* ⭐ **Top Technical Skills:** Horizontal bar chart highlighting core tool demand (BI Tools, Excel, Power BI, SQL, Python).
* ⭐ **Work Arrangement Distribution:** Color-coded distribution breakdown across employment modes.
* ⭐ **Industry Breakdown:** Interactive treemap detailing hiring volume by sector (Technology/Data, Public Sector/Healthcare, Consulting).
* ⭐ **Geographic Distribution:** Interactive UK map mapping hiring concentration across key cities.

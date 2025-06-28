
# 🧠 AI Job Market Analysis Dashboard

This Power BI project provides a comprehensive analysis of global AI job postings based on various parameters including salary, experience level, job title, location, and required skills. The dashboard is designed to help recruiters, job seekers, and analysts gain data-driven insights into the AI job landscape.

---

## 📊 Dashboard Overview

### 1. **Main Dashboard Page**
- **Sum of salary by job title**: Shows the total salary distribution across top AI job roles.
- **Average salary by experience level**: Visualizes average compensation from Entry-Level to Executive roles.
- **Jobs by country** *(Map Visual)*: Geographical distribution of job opportunities across the globe.
- **Experience Level Distribution (Pie Chart)**: Percentage share of jobs by Entry, Mid, Senior, and Executive levels.
- **Job Table**: Displays job title, required skills, and industry.
- **Company-wise Salary Table**: Highlights average salary offered by leading companies.

### 2. **Q&A and Smart Insights Page**
- Utilizes Power BI Q&A to answer dynamic user questions such as:
  - Average salary by company, location, and industry
  - Compare salary versus remote ratio
  - Sort by benefits score
  - Top companies and locations by salary
  - Explore required skills and job types

---

## 🧹 Data Transformation Highlights

The dataset included 15,000 AI job records and the following transformations were applied in Power Query:
- Replaced experience level codes (`EN`, `MI`, `SE`, `EX`) with readable labels.
- Added derived column: **Remote Type** (Remote, Onsite, Hybrid) based on `remote_ratio`.
- Added derived column: **Experience Category** based on `years_experience` using custom logic.
- Converted date fields and computed `days_until_deadline`.
- Cleaned required skills, company size, and currency fields.

---

## 🧠 Key Insights
- **Executive roles** offer the highest average salaries (~$188K).
- **Machine Learning Researchers** and **AI Architects** are among the top-paying job titles.
- **Remote jobs** are widely distributed, with strong opportunities in Europe, North America, and Asia.
- **Popular required skills** include Python, AWS, Azure, GCP, and Deep Learning tools.

---

## 🚀 How to Use

1. Open the `.pbix` file in Power BI Desktop.
2. Explore both pages: Main Analysis & Q&A.
3. Use slicers or ask questions in the Q&A panel to gain custom insights.

---

## 📌 Tools & Technologies
- Power BI
- Power Query (M language)
- DAX (Data Analysis Expressions)
- Microsoft Bing Maps Visual
- CSV (Structured Dataset)

---

## 📬 Contact
For any suggestions or improvements, feel free to connect. 

EMAIL-ID : Parvashah3183@gmail.com 

LinkedIn : https://www.linkedin.com/in/parvashah3183/

---

> 📈 *This dashboard empowers data-driven decision-making in the evolving AI job market.*

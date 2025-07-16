# 📊 AI Job Market EDA Project

A deep-dive Exploratory Data Analysis (EDA) of job listings in the AI domain to uncover trends in hiring, salaries, education, experience, remote work, and growth potential.

---

## 📝 Overview

This project explores key patterns in AI job data, including:
- Which industries are hiring the most
- Which job roles pay the best
- How education and experience affect salary
- Distribution of remote work
- Roles with the highest growth potential (salary per year of experience)
- Impact of years of experience, perks, and remote work on salary

---
## 🧹 Data Cleaning Summary

- Cleaned column names and converted date formats for consistency.  
- Mapped codes to meaningful labels (experience level, company size, employment type).  
- Removed rows with missing key data and prepared skills column using one-hot encoding.  

---

## 📊 EDA Analysis Results

### 🔹 1. Top 10 Hiring Industries
- **Retail**, **Media**, and **Automotive** are the top hiring sectors.
- Other notable industries: Consulting, Technology, Government, Real Estate.

### 🔹 2. Top Paying Job Titles
- **Data Engineer**, **ML Engineer**, **AI Specialist**, and **Head of AI** are the highest paid, with average salaries exceeding **$100,000**.
- All top 10 roles have high six-figure salaries.

### 🔹 3. Average Salary by Education Level
- **Master's degree holders** have the highest average salary, followed by Bachelor's and Associate degrees.
- **PhD holders** surprisingly earn the lowest average salary in this dataset.

### 🔹 4. Job Count by Experience Level
- Job distribution is fairly even across all experience levels: **Mid (MI)**, **Executive (EX)**, **Senior (SE)**, and **Entry (EN)**.

### 🔹 5. Avg. Experience Required by Job Title
- Roles like **Machine Learning Engineer**, **AI Architect**, and **Head of AI** demand the most experience (~6.5+ years).
- Research roles also require high experience levels.

### 🔹 6. Avg. Experience by Industry
- Industries like **Energy**, **Consulting**, and **Media** require the most experience (~6.3 years).
- Telecommunications and Government have slightly lower average experience requirements.

### 🔹 7. Remote Work Distribution
- Fairly balanced:
  - **On-site**: ~33.8%
  - **Hybrid**: ~33.4%
  - **Remote**: ~32.8%

### 🔹 8. Salary Progression by Experience Level
- Salary increases from **Entry** to **Executive** level, with a noticeable dip at **Mid** level (possibly fewer C-level roles or part-time leadership roles included).

### 🔹 9. Remote Ratio by Company Size
- **Small**, **Medium**, and **Large** companies offer nearly equal remote opportunities.
- No significant variation found in remote work availability across company sizes.

### 🔹 10. Growth Potential by Role (Salary / Years of Experience)
- Top roles by growth potential:
  - **Data Analyst**
  - **AI Consultant**
  - **Research Scientist**
  - **Head of AI**
  - **Computer Vision Engineer**
- These roles offer the **best salary returns per year of experience**.

---

## 🔥 Correlation Heatmap Insights (Advanced)

Before diving into individual EDA charts, a correlation heatmap was created using **Salary (USD)** vs. key numerical factors:
- **Years of Experience** had a **positive correlation of 0.74** with salary. This strongly indicates that **experience pays off** in the AI job market.
- **Remote Ratio** had almost **no impact on salary** — whether the job is on-site, hybrid, or remote, salary tends to stay the same.
- **Benefits Score** also showed **no correlation** with salary. This was surprising — **offering better perks doesn’t necessarily mean higher pay**.

These observations were made early on and guided the deeper analysis done later in the project.

---
## 📈 Dashboard Insights
The dashboard enables dynamic filtering, allowing users to view multiple insights tailored to the selected filters, offering a flexible and interactive exploration experience.
![Dashboard Preview](images/dashboard.png)



## 📌 Conclusion

This EDA uncovers valuable insights in the AI job market:
- Retail & Tech are booming with opportunities
- Master’s degree has the highest return
- Remote and hybrid work are becoming mainstream
- Roles like Data Analyst and AI Consultant have strong growth potential
- Experience matters most — perks and remote flexibility don’t affect salary significantly

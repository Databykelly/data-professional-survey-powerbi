# Data Professional Survey — Power BI Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![PowerPoint](https://img.shields.io/badge/PowerPoint-B7472A?style=for-the-badge&logo=microsoftpowerpoint&logoColor=white)

---

## 📋 Project Brief

**Client:** HR and Talent Acquisition Team

**Problem:** The HR team needed to understand the data professional job market — who these professionals are, what they earn, how satisfied they are with their careers, how difficult it is to break into the field, and what they prioritize when considering new opportunities.

**Goal:** Build an interactive dashboard that helps the HR team make better decisions around hiring, compensation benchmarking and talent retention.

---

## 📊 Dataset

- **Source:** Real-world survey of data professionals (Alex the Analyst — Data Professional Survey)
- **Size:** 630 respondents, 28 columns
- **Period:** June 2022
- **Contents:** Job titles, salary ranges, industry, favorite programming languages, job satisfaction scores across 6 dimensions, career background, and demographics including age, gender, country and education level

---

## 🔧 Tools & Skills Used

| Tool | Purpose |
|---|---|
| Power Query | Data cleaning and transformation |
| DAX | Calculated measures and KPIs |
| Power BI Data Model | Table relationships and sort order |
| Power BI Report Canvas | 5-page interactive dashboard |
| PowerPoint | Custom dashboard background design |

---

## 🗂️ Dashboard Pages

### Page 1 — Overview
Headline KPIs giving the HR team an immediate summary:
- Total respondents (630)
- Average age (29.87)
- Average salary ($53.78K)
- Percentage of career switchers (59.05%)

Includes breakdowns by gender, country and job title.

### Page 2 — Salary Analysis
Answers the question: *who earns what, and why?*
- Average salary by job title
- Average salary by country
- Salary range distribution
- Average salary by education level

### Page 3 — Job Satisfaction
Answers the question: *how happy are data professionals?*
- 6 gauge visuals showing satisfaction across salary, work-life balance, coworkers, management, upward mobility and learning
- Overall happiness score by job title

### Page 4 — Career Pathways
Answers the question: *how did people get into data and what do they want?*
- Career switcher breakdown
- Difficulty of breaking into data
- Top job priorities when considering a new role

### Page 5 — Programming Languages
Answers the question: *what technical skills dominate the field?*
- Favorite programming language distribution
- Language breakdown by job title

---

## 💡 Key Insights

### 1. Salary Dissatisfaction Is the Biggest Retention Risk
Salary satisfaction scored just **4.27 out of 10** — the lowest of all six satisfaction dimensions. At the same time, **47% of respondents** said better salary was their number one priority when considering a new job. Companies that fail to address compensation are most at risk of losing their data talent.

> **Recommendation:** HR teams should conduct regular salary benchmarking — particularly for Data Analysts, who make up 60% of the workforce and earn less than Data Scientists and Data Engineers.

### 2. The Data Talent Pool Is Mostly Career Changers
**59% of data professionals** switched from a different career into data. This means the majority of candidates did not follow a traditional academic path into the field. Hiring teams that rely heavily on formal qualifications may be filtering out their strongest candidates.

> **Recommendation:** When hiring, prioritize demonstrated skills and portfolio work over traditional degree requirements.

### 3. Python Is Non-Negotiable
Python dominates across **every single job title** in the survey. Whether hiring a Data Analyst, Data Scientist or Data Engineer — Python proficiency is the single most consistent technical requirement across the field.

> **Recommendation:** Python should be a baseline requirement in all data role job descriptions, with R as a secondary preference for research-heavy or finance roles.

### 4. Education Pays — But Not Linearly
PhD holders earn an average of **$127K** — significantly above all other education levels. However, High School and Bachelor's degree holders show similar salary ranges, suggesting that mid-level education beyond a Bachelor's provides limited salary uplift without a terminal degree.

---

## 🏗️ Project Phases

```
Phase 1 → Power Query     — Cleaned and transformed raw survey data
Phase 2 → Data Modeling   — Built relationships and sort order tables
Phase 3 → DAX             — Created 11 measures including satisfaction scores and KPIs
Phase 4 → Visualizations  — Built 5 report pages answering 10 business questions
Phase 5 → Design          — Applied custom PowerPoint backgrounds and consistent formatting
Phase 6 → GitHub          — Documented and published as portfolio project
```

---

## 📁 Repository Contents

| File | Description |
|---|---|
| `Data_Professional_Survey_Dashboard.pbix` | Power BI dashboard file |
| `Power_BI_Final_Project.xlsx` | Raw dataset |
| `README.md` | Project documentation |
| `/screenshots` | Dashboard page screenshots |

---

## 🚀 How to View the Dashboard

1. Download the `.pbix` file
2. Open with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Use the page tabs at the bottom to navigate between the 5 dashboard pages
4. Use the slicers to filter by country, job title or career switch status

---

## 👤 Author

Built by **Otito** as a portfolio project demonstrating end-to-end Power BI development — from raw data cleaning to business insight delivery.

---

*Data source: Alex the Analyst — Data Professional Survey (2022)*

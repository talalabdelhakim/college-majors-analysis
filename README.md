# College Majors Analytics: Salary, Employment & Gender

[![Kaggle](https://img.shields.io/badge/Kaggle-View%20Notebook-20BEFF?logo=kaggle&logoColor=white)](https://www.kaggle.com/code/talalhakem/collegemajors-analytics-salary-employment-gender)



![Power BI](https://github.com/talalabdelhakim/college-majors-analysis/blob/main/dashboard.png))

An end-to-end analysis of **173 college majors** that explores how salary, employment, unemployment and gender representation vary across fields of study, with an interactive Power BI dashboard on top.

---

## Dashboard

![College Majors Analytics Dashboard](images/dashboard.png)

---

## Project Overview

This project performs an Exploratory Data Analysis (EDA) on the *Economic Guide to College Majors* dataset to answer practical questions for students, career advisors and education analysts:

- Which majors earn the most, and which earn the least?
- Which majors have the highest unemployment rates?
- How is gender balanced across major categories?
- Is there a relationship between a major's salary and its unemployment rate?

## Objectives

- Explore the structure and quality of the dataset
- Clean and prepare the data for analysis
- Analyze the salary distribution across majors and categories
- Examine employment and unemployment rates
- Compare gender representation across majors
- Communicate key insights through clear visualizations and a dashboard

## Key Findings

- The dataset covers **173 majors**, with an average median salary of about **$40K** and an average unemployment rate of about **6.8%**.
- **Petroleum Engineering** ranks as the highest-paying major, with a median salary of roughly **$110K**.
- Engineering majors dominate the top of the salary ranking.
<!-- TODO: add 1-2 findings about gender (e.g. the most female-dominated and male-dominated categories) using numbers from your analysis -->
<!-- TODO: add 1 finding about the relationship between salary and unemployment rate -->

## Dataset

- **Source:** [Economic Guide to College Majors (FiveThirtyEight) on Kaggle](https://www.kaggle.com/)
- **Size:** 173 majors

| Column | Description |
|---|---|
| `Major` | Name of the college major |
| `Major_category` | Broad category the major belongs to |
| `Median` | Median salary of full-time, year-round workers |
| `Employed` | Number of employed graduates |
| `Unemployed` | Number of unemployed graduates |
| `Unemployment_rate` | Share of unemployed graduates |
| `Full_time` | Number of graduates working full-time |
| `ShareWomen` | Share of women among graduates |
| `Men` / `Women` | Number of male and female graduates |

## Methodology

1. **Data understanding:** inspected structure, data types and summary statistics.
2. **Data cleaning:** checked missing values, duplicates and column types, and prepared the data for analysis.
3. **Exploratory analysis:** analyzed salary, employment, unemployment and gender distributions.
4. **Visualization:** built static and interactive charts in Python, plus a dashboard in Power BI.
5. **Insights:** summarized the main patterns and their limits.

## Visualizations

- Salary distribution
- Top 10 highest and lowest median salaries
- Employment analysis
- Unemployment rate analysis
- Gender share distribution (`ShareWomen`)
- Female-dominated vs. male-dominated majors

| Top 10 Highest Paying Majors | Gender Distribution |
|---|---|
| ![Top 10 highest paying majors](images/top10_highest_salaries.png) | ![Gender distribution](images/gender_distribution.png) |

## Tools & Technologies

- **Python:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Dashboard:** Power BI
- **Environment:** Jupyter Notebook / Kaggle

## Repository Structure

```
college-majors-analytics/
├── data/          # dataset (CSV)
├── notebooks/     # analysis notebook
├── images/        # dashboard and chart screenshots
└── README.md
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/talalabdelhakim/college-majors-analytics.git
   cd college-majors-analytics
   ```
2. Install the requirements:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly jupyter
   ```
3. Open the notebook in `notebooks/` and run all cells. The data is loaded from the `data/` folder.

## Limitations

- The data describes **recent graduates** only, so results may not reflect the whole workforce.
- Salary is reported as a **median**, which hides variation within each major.
- Relationships between variables (for example gender share and salary) show association, not causation.

## About Me

**Data Analyst** focused on turning data into clear, actionable insights using Python, SQL and data visualization.

- GitHub: [talalabdelhakim](https://github.com/talalabdelhakim)
- Kaggle: [talalhakem](https://www.kaggle.com/talalhakem)

If you found this project useful, consider giving it a ⭐

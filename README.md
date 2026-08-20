# IT Job Market Analysis 📊

## 📌 Project Overview

The **IT Job Market Analysis** project analyzes thousands of IT job listings collected through web scraping to identify trends in job roles, salaries, skills, experience requirements, locations, and employment types.

The project follows a complete data analysis workflow:

**Web Scraping → Data Cleaning → Exploratory Data Analysis → Visualization → Insights**

---

## 🎯 Objectives

- Analyze current IT job market trends.
- Identify the most in-demand IT job roles.
- Analyze salary distributions across different roles and locations.
- Understand the relationship between experience and salary.
- Identify frequently requested technical skills.
- Analyze employment types and job timings.
- Extract meaningful insights from job market data.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **BeautifulSoup**
- **Requests**
- **Regular Expressions**
- **Jupyter Notebook**

---

## 🔍 Project Workflow

### 1. Web Scraping

Job listing data was collected from online job portals using Python-based web scraping techniques.

The scraped data included information such as:

- Company
- Job Role
- Skills
- Experience
- Location
- Salary
- Employment Type
- Timings
- Posted Date
- Source

---

### 2. Data Cleaning

The raw scraped data was cleaned and transformed to make it suitable for analysis.

Key cleaning steps included:

- Handling missing values
- Removing duplicate records
- Cleaning salary information
- Standardizing experience ranges
- Extracting minimum and maximum experience
- Cleaning skills information
- Standardizing locations
- Cleaning employment type and job timing fields
- Converting columns into appropriate data types

---

### 3. Exploratory Data Analysis

EDA was performed to understand patterns and trends in the IT job market.

Analysis included:

- Salary distribution
- Experience distribution
- Most common job roles
- Most demanded skills
- Location-wise job opportunities
- Company-wise job postings
- Experience vs Salary analysis
- Role vs Salary analysis
- Employment type analysis

---

### 4. Data Visualization

Multiple visualizations were created using **Matplotlib and Seaborn** to communicate the findings effectively.

Examples include:

- Bar charts
- Histograms
- Count plots
- Box plots
- Scatter plots
- Heatmaps
- Distribution plots

---

## 📊 Dataset

After data cleaning and preprocessing, the final dataset contained approximately **7,498 job listings**.

### Main Features

| Column | Description |
|---|---|
| Company | Company offering the job |
| Role | Job position |
| Skills | Required skills |
| Experience | Required experience |
| Location | Job location |
| Salary | Salary information |
| Emp_Type | Employment type |
| Timings | Job timings |
| Posted Date | Date the job was posted |
| Source | Job portal source |
| Min_Exp | Minimum required experience |
| Max_Exp | Maximum required experience |

---

## 📈 Key Insights

The analysis helped identify:

- Which IT roles have the highest demand.
- Which technical skills appear most frequently in job descriptions.
- How salary varies with experience.
- Which locations have more IT job opportunities.
- Salary differences between different job roles.
- Experience requirements across different positions.

---

## 📂 Project Structure

```text
IT_JOB_MARKET_ANALYSIS/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   └── IT_Job_Market_Analysis.ipynb
│
├── visualizations/
│
├── README.md
└── requirements.txt

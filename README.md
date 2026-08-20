# IT Job Market Analysis 📊

## 📌 Project Overview

The **IT Job Market Analysis** project focuses on collecting, cleaning, analyzing, and visualizing IT job market data using Python.

The project follows a complete data analytics workflow:

**Web Scraping → Data Cleaning → Exploratory Data Analysis → Data Visualization → Insights**

Job listing data was collected from online job sources and analyzed to understand trends in job roles, salaries, skills, experience requirements, locations, employment types, and job timings.

---

## 🎯 Objectives

- Collect IT job listing data using Web Scraping
- Clean and preprocess the collected data
- Analyze salary and experience requirements
- Identify the most demanded IT skills and job roles
- Analyze job opportunities by location
- Perform Exploratory Data Analysis (EDA)
- Create meaningful visualizations
- Extract useful insights from the IT job market

---

## 🕷️ 1. Web Scraping

Job listing data was collected from online job portals using Python and web scraping techniques.

### Data collected included:

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

The collected data was stored and further processed for analysis.

---

## 🧹 2. Data Cleaning

The scraped dataset contained missing values, inconsistent formats, and unstructured information.

The following preprocessing steps were performed:

- Handled missing values
- Cleaned salary information
- Extracted minimum and maximum experience
- Converted salary values into numerical format
- Standardized text-based fields
- Processed job skills
- Cleaned location information
- Removed duplicate or irrelevant records
- Prepared the dataset for analysis

The final cleaned dataset contained approximately **7,500 job listings**.

---

## 🔍 3. Exploratory Data Analysis (EDA)

EDA was performed to understand patterns and relationships within the IT job market.

### Analysis included:

- Salary distribution
- Experience vs Salary
- Job roles and demand
- Skills and skill demand
- Location-wise opportunities
- Company-wise job listings
- Employment type analysis
- Job timing analysis
- Experience requirements
- Salary ranges

---

## 📊 4. Data Visualization

Different visualization techniques were used to identify trends and patterns.

### Visualizations included:

- Bar Charts
- Histograms
- Box Plots
- Scatter Plots
- Count Plots
- Distribution Plots
- Grouped Charts
- Pivot-table based analysis

Python libraries such as **Matplotlib** and **Seaborn** were used for visualization.

---

## 💡 Key Insights

The analysis helps understand:

- Which IT roles have higher demand
- Which skills are frequently required
- How salary varies with experience
- Which locations have more job opportunities
- Salary differences between job roles
- Experience requirements across different roles
- Employment patterns in the IT industry

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- BeautifulSoup
- Requests
- Regular Expressions
- Jupyter Notebook
- Excel

---

## 📂 Project Structure

```text
IT_JOB_MARKET_ANALYSIS/
│
├── Web_Scraping.ipynb
├── DataCleaning.ipynb
├── Visualization.ipynb
├── IT_JOB_MARKET_DATA.xlsx
├── Final_Data_AFTER_WEBSCRAPING.xlsx
├── IT_JOB_MARKET_ANALYSIS.pptx
├── README.md
└── .gitattributes

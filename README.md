# IT Job Market Analysis 📊

## 📌 Project Overview

The **IT Job Market Analysis** project focuses on collecting, cleaning, analyzing, and visualizing IT job market data using Python.

The project follows a complete data analytics workflow:

**Web Scraping → Data Cleaning → Exploratory Data Analysis → Data Visualization → Insights**

Job listing data was collected from online job sources and analyzed to understand trends in **job roles, salaries, skills, experience requirements, locations, employment types, and job timings**.

---

## 🎯 Objectives

* Collect IT job market data using web scraping.
* Clean and preprocess raw job listing data.
* Analyze salary and experience requirements.
* Identify frequently occurring job roles and skills.
* Analyze job opportunities across different locations.
* Understand the relationship between experience and salary.
* Create meaningful visualizations from the cleaned dataset.
* Generate insights into IT job market trends.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **BeautifulSoup**
* **Requests**
* **Regular Expressions**
* **Jupyter Notebook**
* **Microsoft Excel**

---

## 🔄 Project Workflow

### 1. Web Scraping

The first stage involved collecting IT job listing information through web scraping using Python.

The collected data included fields such as:

* Company
* Role
* Skills
* Experience
* Location
* Salary
* Employment Type
* Timings
* Posted Date
* Source

The scraping process and data collection are documented in:

**`Web_Scraping.ipynb`**

---

### 2. Data Cleaning & Preprocessing

The raw scraped data was cleaned and prepared for analysis.

The cleaning process included:

* Handling missing values
* Removing duplicate records
* Cleaning salary information
* Standardizing experience values
* Extracting minimum and maximum experience
* Cleaning and standardizing categorical data
* Processing skills and location information
* Converting data into appropriate formats
* Preparing the final dataset for analysis

The complete cleaning process is available in:

**`DataCleaning.ipynb`**

---

### 3. Exploratory Data Analysis & Visualization

The cleaned dataset was analyzed to identify patterns and trends in the IT job market.

The analysis covered areas such as:

* Job role distribution
* Salary distribution
* Experience requirements
* Skills demand
* Location-wise job opportunities
* Company-wise job postings
* Employment types
* Job timings
* Experience vs. Salary
* Role vs. Salary

Visualizations were created using **Matplotlib and Seaborn**.

The analysis and visualizations are available in:

**`Visualization.ipynb`**

---

## 📊 Dataset

The project contains both the original scraped dataset and the processed dataset.

### Raw Dataset

**`IT_JOB_MARKET_DATA.xlsx`**

Contains the job listing data collected during the web scraping stage.

### Final Dataset

**`Final_Data_AFTER_WEBSCRAPING.xlsx`**

Contains the cleaned and processed dataset used for analysis.

The final dataset contains approximately **7,498 job listings** with information related to companies, roles, skills, experience, locations, salaries, employment types, timings, posting dates, and sources.

---

## 📋 Dataset Features

| Column      | Description                         |
| ----------- | ----------------------------------- |
| Company     | Company offering the job            |
| Role        | Job position                        |
| Skills      | Skills mentioned in the job listing |
| Experience  | Required experience                 |
| Location    | Job location                        |
| Salary      | Salary information                  |
| Emp_Type    | Employment type                     |
| Timings     | Job timings                         |
| Posted Date | Job posting date                    |
| Source      | Source of the job listing           |
| Min_Exp     | Minimum required experience         |
| Max_Exp     | Maximum required experience         |

---

## 📈 Analysis Performed

The project analyzes the IT job market from multiple perspectives.

### Job Roles

* Distribution of different IT job roles
* Most frequently posted positions
* Role-wise salary analysis

### Salary Analysis

* Salary distribution
* Salary comparison across roles
* Salary comparison based on experience

### Experience Analysis

* Experience requirements across job roles
* Minimum and maximum experience requirements
* Relationship between experience and salary

### Skills Analysis

* Frequently requested technical skills
* Skill demand across job listings

### Location Analysis

* Distribution of jobs across locations
* Location-wise job opportunities

### Other Analysis

* Employment type distribution
* Job timing analysis
* Company-wise job postings
* Source-wise job listings

---

## 📊 Visualizations

The project includes different types of visualizations, including:

* Bar Charts
* Count Plots
* Histograms
* Box Plots
* Scatter Plots
* Heatmaps
* Distribution Plots

These visualizations were used to identify patterns, relationships, and trends in the collected job market data.

---

## 📁 Repository Structure

```text
IT_JOB_MARKET_ANALYSIS/
│
├── Web_Scraping.ipynb
├── DataCleaning.ipynb
├── Visualization.ipynb
│
├── IT_JOB_MARKET_DATA.xlsx
├── Final_Data_AFTER_WEBSCRAPING.xlsx
│
├── IT_JOB_MARKET_ANALYSIS.pptx
│
└── README.md
```

### File Description

| File                                | Description                                         |
| ----------------------------------- | --------------------------------------------------- |
| `Web_Scraping.ipynb`                | Python notebook containing the web scraping process |
| `DataCleaning.ipynb`                | Data cleaning and preprocessing                     |
| `Visualization.ipynb`               | EDA and data visualization                          |
| `IT_JOB_MARKET_DATA.xlsx`           | Raw scraped job market data                         |
| `Final_Data_AFTER_WEBSCRAPING.xlsx` | Cleaned and processed dataset                       |
| `IT_JOB_MARKET_ANALYSIS.pptx`       | Project presentation                                |
| `README.md`                         | Project documentation                               |

---

## 💡 Key Skills Demonstrated

This project demonstrates practical experience in:

* Web Scraping
* Data Collection
* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Data Visualization
* Salary Analysis
* Statistical Analysis
* Feature Extraction
* Python Programming
* Pandas & NumPy
* Matplotlib & Seaborn
* Insight Generation

---

## 🚀 How to Explore the Project

1. Start with **`Web_Scraping.ipynb`** to understand how the job data was collected.
2. Open **`DataCleaning.ipynb`** to see the data cleaning and preprocessing steps.
3. Open **`Visualization.ipynb`** to explore the EDA and visualizations.
4. Use **`Final_Data_AFTER_WEBSCRAPING.xlsx`** to view the final cleaned dataset.
5. Refer to **`IT_JOB_MARKET_ANALYSIS.pptx`** for the project presentation.

---

## 👨‍💻 Author

**GuruPreeth Reddy**

B.Tech – Computer Science & Engineering

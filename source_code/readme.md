# 📊 LinkedIn Job Postings Analysis

## 📌 Project Overview

This project analyzes LinkedIn job postings to identify trends and patterns in the job market. The analysis focuses on job roles, locations, companies, employment types, experience levels, skills, salary information, and remote-work opportunities.

Python and popular data analysis libraries are used to clean, process, explore, and visualize the dataset.

---

## 🎯 Objectives

The main objectives of this project are to:

- Analyze the most common job titles.
- Identify locations with the highest number of job postings.
- Analyze companies based on the number of job postings.
- Understand the distribution of experience levels.
- Identify frequently associated job skills.
- Analyze salary availability and salary distribution.
- Compare salary levels across experience categories.
- Examine remote-work opportunities.
- Identify important patterns in LinkedIn job postings.

---

## 📂 Dataset

The project uses the **LinkedIn Job Postings Dataset** containing job posting information and related datasets.

### Main Dataset

`job_postings.csv`

The dataset contains information such as:

- Job ID
- Company ID
- Job Title
- Job Description
- Minimum Salary
- Median Salary
- Maximum Salary
- Work Type
- Location
- Experience Level
- Application Type
- Remote Work Information
- Views
- Applications
- Posting Date
- Currency
- Compensation Type

### Additional Datasets Used

- `companies.csv`
- `job_skills.csv`

The company dataset was merged with the main job-posting dataset to obtain company names, while the job-skills dataset was used to analyze frequently associated skills.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Google Colab**
- **Jupyter Notebook**

---

## 🧹 Data Cleaning

The following data-cleaning steps were performed:

- Checked and removed missing job descriptions.
- Checked duplicate records.
- Verified duplicate job IDs.
- Handled missing experience levels by assigning `Not Specified`.
- Created salary availability indicators.
- Created remote-work status categories.
- Checked numerical columns for negative values.
- Validated salary ranges.
- Cleaned text columns and job titles.
- Created a standardized job-title column.
- Created salary range and representative salary columns.
- Converted posting timestamps into date format.
- Extracted year and month information from posting dates.
- Merged company names with job postings.

---

## 📊 Exploratory Data Analysis

### 1. Job Categories

Analyzed:

- Most common job titles
- Job postings by work type

### 2. Job Locations

Analyzed:

- Top job-posting locations
- Percentage of postings by major locations

### 3. Company Analysis

Analyzed:

- Companies with the highest number of job postings
- Distribution of companies by company-size category

### 4. Experience & Skills

Analyzed:

- Job postings by experience level
- Most frequently associated job skills

### 5. Salary Analysis

Analyzed:

- Salary availability
- Salary distribution
- Average salary by experience level

### 6. Remote / On-site Jobs

Analyzed:

- Remote-work status
- Remote-work status across experience levels

---

## 🔍 Key Findings

Some important observations from the analysis include:

- **Full-time employment** represents the largest share of job postings.
- **Mid-Senior level** positions form a large portion of the dataset, followed by postings where experience level was not specified and Entry-level positions.
- **IT, Sales, Management, Manufacturing, and Business Development** are among the frequently associated skill categories.
- Major job locations include the **United States, New York, Chicago, Houston, and Atlanta**.
- Several companies have substantially more job postings than others within this dataset.
- Salary information is not available for every job posting.
- Salary values vary across different experience levels.
- A significant portion of postings does not specify remote-work information.

> These findings describe patterns within this dataset and should not be interpreted as a complete representation of the entire LinkedIn job market.

---

## 📁 Project Structure

```text
LinkedIn-Job-Postings-Analysis/
│
├── LinkedIn_Job_Postings_Analysis.ipynb
├── linkedin_job_postings_cleaned.csv
├── README.md
│
└── dataset/
    ├── job_postings.csv
    ├── companies.csv
    └── job_skills.csv
```

---

## 📈 Project Workflow

```text
Data Collection
      ↓
Data Loading
      ↓
Data Cleaning
      ↓
Data Transformation
      ↓
Exploratory Data Analysis
      ↓
Data Visualization
      ↓
Insights & Findings
      ↓
Conclusion
```

---

## 💡 Conclusion

This project demonstrates how Python-based data analysis can be used to extract meaningful insights from job-posting data.

By analyzing job roles, companies, locations, experience levels, skills, salaries, and remote-work information, the project provides a structured overview of patterns present in the LinkedIn job-posting dataset.

The project also demonstrates practical skills in **data cleaning, data transformation, exploratory data analysis, visualization, and interpretation of datasets**.

---

## 👩‍💻 Author

**Shambhavi Sinha**

BCA Student | Data Science & Data Analytics Enthusiast

### Skills Demonstrated

- Python
- Pandas
- NumPy
- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Statistical Analysis
- SQL
- Power BI
- Tableau

---

## Project Highlights

Dataset: LinkedIn Job Postings  
Tools: Python, Pandas, NumPy, Matplotlib, Seaborn  
Environment: Google Colab  
Project Type: Data Analysis / Exploratory Data Analysis
# Analysis of the Labor Market in Data Science

## Objective
This project aims to clean, transform, and process **Data Science job postings** from Glassdoor to extract meaningful insights into salary trends, required skills, experience levels, and other job-related attributes.

## Dataset
The dataset used is **Uncleaned_DS_jobs.csv**, containing job postings for Data Science roles, including job descriptions, salaries, company details, and more.

## Data Cleaning & Transformation
The following steps were performed to clean and structure the data:
- **Salary Processing:** Extracted salary estimates and converted them into numerical values.
- **Skill Extraction:** Identified key technical skills (e.g., Python, SQL, AWS) from job descriptions.
- **Experience Level Categorization:** Classified jobs into Entry-level, Mid-level, and Senior roles based on job descriptions.
- **Education Level Identification:** Extracted required education levels (Bachelor's, Master's, PhD).
- **Company Data Standardization:** Cleaned company names, extracted city/state from locations, and standardized company size and revenue data.
- **Competitor Analysis:** Counted the number of competitors for each company.
- **Data Type Adjustments:** Converted categorical and numerical fields to appropriate data types.
- **Outlier Detection:** Identified and handled outliers in salary and experience level data.

## Data Export
The cleaned dataset is saved as **Cleaned_DS_jobs.csv**, ensuring structured and analysis-ready data.

## Exploratory Data Analysis (EDA)
To understand job market trends, various visualizations were created:
- **Top 10 Most In-Demand Skills**
- **Top Cities with the Most Data Science Job Opportunities**
- **Competitors vs Salary Impact**
- **Salary Distribution by Experience Level**
- **Correlation Heatmap Between Numerical Variables**
- **Overall Salary Distribution**
- **Salary Trends Over Time**

## Technologies Used
- **Python** (pandas, numpy, re, seaborn, matplotlib)
- **Data Manipulation & Cleaning:** pandas, numpy, regex
- **Visualization:** seaborn, matplotlib
- **Jupyter Notebook** for analysis and visualization

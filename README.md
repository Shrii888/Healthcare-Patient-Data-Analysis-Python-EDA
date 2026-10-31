# 🏥 Healthcare Patient Data Analysis – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a healthcare dataset containing patient demographics, medical conditions, hospital admissions, billing information, medications and test results.

The objective is to explore healthcare data using Python, identify meaningful patterns, understand patient characteristics and generate insights through statistical analysis and data visualization.

## 🎯 Business Problem

Healthcare organizations generate large amounts of patient data. Analyzing this information can help understand patient demographics, medical conditions, hospital admission patterns and billing trends.

This project explores these areas to identify patterns and summarize findings that can support better understanding of hospital operations.

## 🎯 Project Objectives

- Understand the structure and characteristics of the dataset.
- Identify missing values and duplicate records.
- Perform data cleaning and preprocessing.
- Analyze patient demographics and age distribution.
- Explore medical conditions and admission patterns.
- Investigate hospital billing amounts.
- Analyze hospital length of stay.
- Identify relationships between different variables.
- Detect potential outliers.
- Generate meaningful business insights.

## 🛠️ Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Development environment |

## 📂 Dataset Description

The dataset contains **55,500 initial records and 15 columns**.

### Dataset Columns

- Name
- Age
- Gender
- Blood Type
- Medical Condition
- Date of Admission
- Doctor
- Hospital
- Insurance Provider
- Billing Amount
- Room Number
- Admission Type
- Discharge Date
- Medication
- Test Results

## 🔍 Project Workflow

### 1. Data Loading and Understanding
- Imported the dataset using Pandas.
- Examined the first and last records.
- Checked dataset dimensions, column names and data types.
- Generated descriptive statistical summaries.

### 2. Data Cleaning and Preprocessing
- Checked missing values.
- Identified and removed 534 exact duplicate records.
- Converted admission and discharge dates into datetime format.
- Created a new feature called `Length of Stay`.
- Investigated unusual billing values.

After duplicate removal, the dataset contained **54,966 records and 15 columns**.

### 3. Univariate Analysis

Analyzed individual variables to understand their distributions.

Key areas:
- Gender distribution
- Age distribution
- Medical condition distribution
- Admission type distribution
- Billing amount distribution
- Length of hospital stay
- Test result distribution

### 4. Bivariate Analysis

Explored relationships between two variables.

Analyses included:
- Gender vs Length of Stay
- Medical Condition vs Billing Amount
- Admission Type vs Billing Amount
- Age vs Billing Amount
- Admission Type vs Length of Stay

### 5. Multivariate Analysis

Explored multiple variables together to identify patterns.

Analyses included:
- Medical Condition vs Gender vs Admission Type
- Medical Condition vs Admission Type vs Billing Amount

### 6. Correlation Analysis

- Calculated correlations between numerical variables.
- Created a correlation heatmap.
- Examined linear relationships between numerical features.

### 7. Outlier Analysis

- Used boxplots to visualize numerical distributions.
- Applied the Interquartile Range (IQR) method.
- Investigated potential outliers in Billing Amount and Length of Stay.

## 📊 Key Analysis Areas

The project explores the following business questions:

1. How are patients distributed across genders and age groups?
2. Which medical conditions occur most frequently?
3. Which admission types are most common?
4. Does average billing vary across medical conditions?
5. Does patient age have a relationship with billing amount?
6. Do different admission types have different hospital stay durations?
7. Which medications and test results are most frequently recorded?

## 💡 Key Learnings

Through this project, I gained practical experience in:

- Working with real-world-style structured datasets.
- Performing data cleaning using Pandas.
- Handling duplicate records.
- Converting date columns and creating new features.
- Applying descriptive statistics.
- Performing univariate, bivariate and multivariate analysis.
- Creating visualizations using Matplotlib and Seaborn.
- Identifying potential outliers using the IQR method.
- Translating analytical results into business observations.

## 🏁 Conclusion

This project demonstrates the use of Python for exploratory data analysis in the healthcare domain.

Through data cleaning, statistical exploration and visualization, the project examines patient demographics, medical conditions, hospital admission patterns, billing information and length of stay.

The analysis helped develop practical skills in data exploration, identifying patterns and communicating findings through data.

## 👩‍💻 Author

**Shriya Verma**

Aspiring Data Analyst

**Skills:** Python | Pandas | NumPy | Matplotlib | Seaborn | Exploratory Data Analysis

---

⭐ If you find this project useful, feel free to explore the notebook and its visualizations.

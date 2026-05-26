# ABC Corporation Attrition Analysis

People Analytics case study focused on employee attrition and retention insights at **ABC Corporation**.

This project was developed as part of the **Adalab Data Analytics & AI Bootcamp** and has been adapted for portfolio purposes.

---

## Overview

The goal of this project was to analyze employee attrition at **ABC Corporation** in order to identify key patterns, potential risk factors and actionable recommendations to improve talent retention.

The project follows a complete data analytics workflow, from exploratory data analysis and data cleaning to visualization, insight generation and ETL integration with MySQL.

---

## Business Context

Employee attrition is a key challenge for People teams because it can directly impact business continuity, team performance, employee engagement and hiring costs.

This project simulates a People Analytics scenario where HR stakeholders need to understand which factors are associated with employee turnover and identify where retention actions should be prioritized.

---

## Project Context

This was a **group project** developed during the Adalab Data Analytics & AI Bootcamp.

The original project was created by the **ANDROMEDA TECH** team and focused on talent optimization and employee retention at ABC Corporation.

---

## Objective

The main objectives of this project were to:

- Analyze the main factors associated with employee attrition.
- Identify employee segments with higher attrition risk.
- Explore the relationship between attrition, job level, overtime, salary and satisfaction.
- Generate actionable People Analytics insights.
- Build a complete data workflow covering EDA, cleaning, visualization and ETL.
- Support HR decision-making through data-driven recommendations.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- MySQL
- SQLAlchemy
- ETL Processes
- Data Visualization
- People Analytics

---

## Analysis Workflow

### 1. Exploratory Data Analysis

The first phase focused on understanding the dataset structure and identifying potential data quality issues.

This included:

- Dataset validation
- Null value detection
- Duplicate review
- Inconsistency detection
- Variable understanding
- Initial attrition exploration

### 2. Data Cleaning and Transformation

The second phase focused on preparing the dataset for analysis.

This included:

- Removing redundant variables
- Cleaning categorical variables
- Handling missing values
- Converting data types
- Enriching variables
- Preparing a clean dataset for analysis and visualization

### 3. Analysis and Visualization

The third phase focused on analyzing key attrition drivers and communicating insights visually.

This included:

- Attrition analysis by employee segment
- Job level analysis
- Overtime impact analysis
- Salary and satisfaction analysis
- Identification of critical employee groups
- Visual storytelling through charts and heatmaps

### 4. ETL with MySQL

As a bonus phase, the clean dataset was loaded into a relational database.

This included:

- Using the cleaned dataset generated in the transformation phase
- Connecting to MySQL using SQLAlchemy
- Creating the `ABC_Corporation` schema
- Creating the `employees_attrition` table
- Loading the DataFrame into MySQL

---

## Key Insights

The analysis revealed several relevant patterns related to employee attrition:

- Attrition was higher among lower job levels.
- Overtime showed a significant relationship with employee turnover.
- The combination of lower job level and high workload appeared as a critical risk segment.
- Salary seemed to influence attrition differently depending on employee level.
- Employees who left the company tended to show lower satisfaction levels.

---

## Featured Visualization

One of the key visualizations in the project is an attrition heatmap showing how the combination of **job level** and **overtime** influences employee turnover.

This visualization helps identify critical segments where People teams could prioritize retention actions.

---

## Recommendations

Based on the analysis, the following People actions were recommended:

- Reduce excessive overtime and monitor workload distribution.
- Strengthen onboarding and early-tenure support.
- Define clearer career development paths.
- Improve employee satisfaction initiatives.
- Design long-term retention incentives for critical segments.
- Prioritize interventions in high-risk employee groups.

---

## Data Availability

The original raw and processed datasets are not included in this repository due to file size limitations and project usage restrictions.

This repository focuses on documenting the analytical workflow, methodology, code structure, visual outputs and key insights developed during the project.

A small sample dataset may be added in the future to illustrate the structure of the original data.

---

## Project Structure

```bash
assets/
└── attrition_heatmap.png

docs/
├── talent-retention-documentation.md
├── user-stories.pdf
└── final-demo-presentation.pdf

files/
└── hr-data.csv

notebooks/
├── 01_eda.ipynb
├── 02_data_cleaning_transformation.ipynb
├── 03_visualization_analysis.ipynb
└── 04_etl_mysql_bonus.ipynb

src/
├── missing_values_support.py
└── visualization_support.py

README.md
.gitignore
```

> Note: File names may vary depending on the final uploaded files. The original raw and processed data folders are not included in this portfolio version.

---

## Group Project

This project was developed collaboratively as a group project during the Adalab Data Analytics & AI Bootcamp.

The repository is part of my personal portfolio and documents my contribution to the project, while recognizing that the original work was developed by the team.

---

## My Contribution

Within the project, I was directly involved in the analytical execution of the People Analytics workflow, from data exploration and preparation to insight generation and final documentation.

My main contributions included:

- Explored and analyzed HR-related data to identify relevant attrition patterns.
- Cleaned, structured and transformed employee data for analysis.
- Developed analytical views focused on attrition, job level, overtime, satisfaction and retention risk.
- Built and interpreted visualizations to communicate People Analytics insights clearly.
- Participated in the ETL workflow for loading cleaned data into MySQL.
- Interpreted results from an HR and business decision-making perspective.
- Developed project documentation and contributed to the final presentation of the methodology, analytical process and key insights.

---

## Key Skills Applied

- People Analytics
- HR Data Analytics
- Employee attrition analysis
- Workforce segmentation
- Exploratory Data Analysis
- Data cleaning and transformation
- Data visualization
- ETL with MySQL
- SQLAlchemy
- Business-oriented recommendations
- Data storytelling
- Team collaboration

---

## Repository Notes

This repository is part of my personal People Analytics and Data Analytics portfolio.

The project was originally developed collaboratively during the Adalab Data Analytics & AI Bootcamp and has been adapted to highlight its analytical, technical and business value.

---

## Contributor

Ana García Sánchez

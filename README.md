
# Customer Churn Analysis at Telco Marketing Campaign

### Author: Azeez Akintonde  
**Date:** May 28, 2024

## Overview

This project aims to analyze customer churn in the Bangor-Telco marketing campaign by employing machine learning and data science techniques. Through dataset examination, preprocessing, and predictive modeling, the analysis identifies factors contributing to churn, providing actionable insights to potentially mitigate it.

## Table of Contents

- [Project Methodology](#project-methodology)
  - [1. Database Setup](#1-database-setup)
  - [2. Data Loading](#2-data-loading)
  - [3. Data Exploration and Pre-processing](#3-data-exploration-and-pre-processing)
  - [4. Statistical Analysis in R](#4-statistical-analysis-in-r)
  - [5. Data Visualization in Power BI](#5-data-visualization-in-power-bi)
  - [6. Findings and Recommendations](#6-findings-and-recommendations)
  - [7. Project Documentation](#7-project-documentation)

---

## Project Methodology

### 1. Database Setup

- **Objective:** Create a MySQL database to store and manage customer churn data.
- **Actions:**
  - Install MySQL and configure user credentials.
  - Create a database named **'world'** to hold customer churn information.
  - Design and create a table (`bangortelco_customers`) within the **'world'** database to store relevant customer data fields.

### 2. Data Loading

- **Objective:** Retrieve customer churn data from the MySQL database for analysis in R and Power BI.
- **Actions:**
  - Connect R to the MySQL database using the **`RMySQL`** package.
  - Use SQL queries to extract data from the **'telco'** table.
  - Load the data into an R dataframe (`bangorTelco_MarketingCampaign`) for statistical analysis.

### 3. Data Exploration and Pre-processing

- **Objective:** Understand the dataset structure and prepare it for analysis.
- **Actions:**
  - Perform Exploratory Data Analysis (EDA) to gain insights into data structure and patterns.
  - Identify missing values, assess summary statistics, and verify data types.
  - Preprocess data by handling missing values, adjusting data types, and addressing outliers.

### 4. Statistical Analysis in R

- **Objective:** Apply statistical methods to uncover patterns and relationships within customer churn data.
- **Actions:**
  - Fit **Decision Tree** and **Logistic Regression** models to understand predictive factors.
  - Use the **k-Nearest Neighbors (KNN)** model to evaluate churn behavior.
  - Generate visualizations to highlight insights derived from the analysis.

### 5. Data Visualization in Power BI

- **Objective:** Create visualizations that effectively communicate findings related to customer churn.
- **Actions:**
  - Use Power BI's R integration to run R scripts, enhancing data exploration.
  - Develop visualizations such as confusion matrices, decision tree plots, and K-means clustering charts.
  - Incorporate these visuals into Power BI dashboards for an interactive, comprehensive view of churn trends.

### 6. Findings and Recommendations

- **Objective:** Summarize key findings and provide actionable recommendations.
- **Actions:**
  - Combine insights from R and Power BI analyses to identify churn drivers.
  - Outline recommendations to reduce churn based on identified patterns.
  - Suggest areas for further research to refine churn prevention strategies.

### 7. Project Documentation

- **Objective:** Document all methodologies, code, and results for reproducibility.
- **Actions:**
  - Compile a detailed project report including code snippets, visual outputs, and methodologies.
  - Ensure documentation clarity to support future reference and project replication.

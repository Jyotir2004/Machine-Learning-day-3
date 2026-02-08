This README content is based on the data cleaning and visualization techniques demonstrated in the ml day 3 (1).ipynb notebook.

Loan Payment Data Cleaning and Exploratory Analysis
This project focuses on the essential first steps of the machine learning pipeline: Data Cleaning and Exploratory Data Analysis (EDA). Using a loan payments dataset, this notebook demonstrates how to handle missing values and visualize data distributions to gain actionable insights.

Project Overview
The primary goal of this project is to address data quality issues and understand the underlying patterns in customer loan repayment behavior.

Key Data Processing Steps:
Missing Value Identification: Systematically identifying null entries across features such as paid_off_time and past_due_days using .isnull().sum().

Forward Fill Imputation: Demonstrating the use of the ffill method to handle missing data by propagating the last valid observation forward.

Statistical Summaries: Utilizing .describe() to understand the central tendency, dispersion, and shape of the dataset's distribution.

Exploratory Data Visualization:

Distribution Plots: Using Seaborn's displot to visualize the distribution of applicant ages.

Count Plots: Analyzing the frequency of different loan statuses (e.g., PAIDOFF, COLLECTION) to understand repayment trends.

Technologies Used
Python 3

Pandas: For data manipulation and cleaning.

Seaborn: For advanced statistical data visualization.

Matplotlib: For creating static and interactive visualizations.

Dataset Features
The analysis is performed on the Loan payments data.csv, which includes:

Loan Details: loan_status, Principal, terms.

Timestamps: effective_date, due_date, paid_off_time.

Demographics: age, education, Gender.

Risk Metrics: past_due_days..

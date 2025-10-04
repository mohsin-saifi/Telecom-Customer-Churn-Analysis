# Telecom-Customer-Churn-Analysis
Customer Churn Analysis
This repository contains a comprehensive analysis of customer churn data using Python and various data analysis libraries. The project explores factors that influence customer churn and provides insights through data visualization.

Project Overview
The analysis focuses on understanding customer behavior and identifying patterns that lead to churn in a telecommunications company. The dataset contains customer information including demographics, service subscriptions, billing information, and churn status.

Dataset
The dataset (Customer Churn.csv) contains 7,043 customer records with 21 features including:

Customer Demographics: gender, SeniorCitizen status, Partner, Dependents

Service Information: tenure, PhoneService, MultipleLines, InternetService

Additional Services: OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies

Contract Details: Contract type, PaperlessBilling, PaymentMethod

Billing Information: MonthlyCharges, TotalCharges

Target Variable: Churn (Yes/No)

Key Features
Data Preprocessing
Handled missing values in TotalCharges column by replacing blanks with "0"

Converted TotalCharges from object to float data type

Transformed SeniorCitizen values (0/1) to "no"/"yes" for better interpretability

Exploratory Data Analysis
Churn Distribution: 26.54% of customers have churned

Demographic Analysis: Gender and Senior Citizen status in relation to churn

Data Quality Checks: Verified no missing values and no duplicate customer IDs

Visualizations
Count plots showing churn distribution across different customer segments

Pie charts displaying churn percentages

Statistical summaries of numerical features

Technologies Used
Python 3.x

Pandas: Data manipulation and analysis

NumPy: Numerical computations

Matplotlib: Data visualization

Seaborn: Statistical data visualization

Key Findings
The dataset shows a churn rate of approximately 26.54%

Initial analysis reveals no missing values after preprocessing

The dataset contains unique customer IDs with no duplicates

Both gender and senior citizen status show interesting patterns in relation to churn

Getting Started
Prerequisites
Python 3.x

Jupyter Notebook

Required Python packages: pandas, numpy, matplotlib, seaborn

Installation
Clone this repository

Install required packages:

bash
pip install pandas numpy matplotlib seaborn jupyter
Launch Jupyter Notebook:

bash
jupyter notebook
Open TCA.ipynb and run the cells

Usage
The notebook is organized in a logical flow:

Data loading and initial inspection

Data cleaning and preprocessing

Exploratory data analysis

Visualization of key insights

Statistical summaries

Future Work
Implement machine learning models for churn prediction

Feature engineering to create more predictive variables

Deep dive into service-related factors affecting churn

Customer segmentation analysis

Time-series analysis of customer tenure

Contributing
Contributions are welcome! Please feel free to submit pull requests or open issues for suggestions and improvements.

License
This project is open source and available under the MIT License.

Contact
For questions or suggestions, please open an issue in this repository.


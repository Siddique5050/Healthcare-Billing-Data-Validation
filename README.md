Healthcare Billing Data Validation & Analytics

📌 Project Overview

This project focuses on cleaning, validating, and analyzing healthcare billing data using **Microsoft Excel and Power BI**.

The dataset is a **synthetic healthcare billing dataset** created to simulate real-world billing data. It contains common data-quality issues such as duplicate records, missing values, inconsistent entries, and invalid records.

The main goal of this project was to clean and validate the data in Excel and then use Power BI to create an interactive dashboard for analyzing claims, billing amounts, insurance coverage, patient payments, and payment status.

🎯 Project Objectives

- Clean and prepare raw healthcare billing data
- Identify and remove duplicate records
- Handle missing and invalid values
- Validate billing and financial information
- Standardize inconsistent categorical data
- Prepare a final clean dataset for analysis
- Create an interactive Power BI dashboard
- Analyze billing, payments, departments, and insurance providers
- Present useful business insights through dashboard visualizations

🗂️ Dataset

The dataset contains healthcare billing information such as:

- Patient ID
- Patient Name
- Age
- Gender
- Provider
- Department
- Service Date
- Billing Date
- Insurance Provider
- Procedure
- Diagnosis
- Claim ID
- Claim Amount
- Insurance Coverage
- Patient Payment
- Payment Status

The original dataset contained **15,100 records**.

After identifying and removing **100 redundant duplicate records**, the final dataset contained **15,000 records**.

🧹 Data Cleaning & Validation

The data cleaning process was performed in Microsoft Excel.

### Cleaning Steps

1. Checked for duplicate Claim IDs
2. Identified missing values
3. Validated patient ages
4. Validated claim amounts
5. Checked billing dates against service dates
6. Standardized gender values
7. Standardized payment status values
8. Cleaned provider, department, procedure, and diagnosis names
9. Handled missing patient names
10. Handled missing insurance provider values
11. Validated insurance coverage and patient payment amounts
12. Performed final financial validation

Final Validation

After completing the cleaning and validation process:

- Original records: **15,100**
- Duplicate records removed: **100**
- Final clean records: **15,000**
- Remaining validation issues: **0**

📊 Power BI Dashboard

The cleaned dataset was imported into Power BI to create an interactive healthcare billing analytics dashboard.

Dashboard Includes

- Total Claims
- Total Claim Amount
- Total Insurance Coverage
- Total Patient Payment
- Average Claim Amount
- Claims by Department
- Payment Status Distribution
- Claim Amount by Department
- Monthly Claims Trend
- Average Claim Amount by Department
- Claim Amount by Insurance Provider
- Patient Payment by Department

Interactive Filters

The dashboard includes interactive filters for:

- Department
- Payment Status

These filters allow users to explore specific parts of the dataset and understand the data more easily.

💡 Business Insights

The dashboard helps analyze:

- Overall healthcare claim activity
- Billing amounts across departments
- Insurance coverage and patient payments
- Paid, Pending, and Rejected claims
- Monthly claim trends
- Billing activity across insurance providers
- Department-level payment patterns
- Overall data quality after the cleaning process

🛠️ Tools & Technologies

Microsoft Excel

- Data Cleaning
- Data Validation
- Data Transformation
- Excel Tables
- Formulas
- Duplicate Detection
- Data Quality Checks

Power BI

- Data Visualization
- DAX Measures
- KPI Cards
- Interactive Filters
- Dashboard Development
- Business Insights

📁 Project Structure

Healthcare-Billing-Data-Validation/
│
├── Dataset/
│   ├── Healthcare_Billing_Raw_Data.csv
│   └── Healthcare_Billing_Clean_Data.xlsx
│
├── Excel/
│   └── Healthcare_Billing_Data_Validation.xlsx
│
├── PowerBI/
│   └── Healthcare_Billing.pbix
│
├── Screenshots/
│   ├── Dashboard.png
│   └── Business_Insights.png
│
└── README.md

Raw Healthcare Billing Data
            ↓
      Data Cleaning
            ↓
     Data Validation
            ↓
    Duplicate Removal
            ↓
    Final Clean Dataset
            ↓
       Power BI
            ↓
   Interactive Dashboard
            ↓
     Business Insights


📌 Key Learning Outcomes

Through this project, I gained practical experience in:

Data cleaning and validation
Handling real-world-style data-quality issues
Excel-based data analysis
Data transformation
Financial validation
Power BI dashboard development
DAX measures
KPI reporting
Interactive data visualization
Business-oriented data analysis

👤 Author

MD AQUIB SIDDIQUE

BCA Graduate | Data Analyst | MIS Analyst

Skills: Excel | SQL | Power BI | Python | MySQL | Data Cleaning | Data Validation | Data Visualization | Dashboard Development | MIS Reporting

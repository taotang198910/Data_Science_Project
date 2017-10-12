# SF Salary

You can view `SF_Salaries.V2.ipynb` directly on github, or clone the repository and open on Jupyter Notebook.

## Introduction
For this project, I have analyzed data from Kaggle. This data contains the names, job title, and compensation such as BasePay,OtherPay,Benefits,TotalPay,and TotalBenefitsPay for San Francisco city employees on an annual basis from 2011 to 2014.

## Data Cleaning
This project involves taking messy data, then cleaning it up and doing analysis. Most part of this project is dealing with data cleaning. There are a few specific things what I have done in cleaning data:

  1. Filling in missing values
  2. Correcting erroneous datatype: some object datatype shoudl be numeric.
  3. Normalizing values: convert all values of EmployeeName and JobTitle to uppercase and prepare for future analysis.
  4. Standardizing categories: In many cases where data is collected from users directly – particularly using free text fields – spelling      mistakes, language differences or other factors will result in a given answer being provided in multiple ways. For example, under the JobtTitle column, data inevitably contain multiple spellings of the same job title (e.g. ``CHIEF OF DEPARTMENT, (FIRE DEPARTMENT)``,  ``CHIEF, FIRE DEPARTMENT``)

## Exploratory Data Analysis
Using Matplotlib and Seaborn to do EAD by answering follow questions:
  1. Should use mean or median to do following EAD by detecting outliers?
  2. Median value of BasePay,TotalPay and TotalBenefitsPay of each year.
  3. Top 10 TotalPay jobs in 2011 and 2014.
  4. TotalPay Distribution of Registered Nurse and FireFighter over years.
  5. What are the median TotalPay and BasePay of Registered Nurse and FireFighter each year? How have their salaries changed over time? How are BasePay, OvertimePay, and Benefits allocated between them?
  
  
## Requirements
* Python3
* Numpy
* Pandas
* Matplotlib
* Seaborn
* Missingno
* Jupyternotebook

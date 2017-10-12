# SF Salary

You can view `SF_Salaries.V2.ipynb` directly on github, or clone the repository and open on Jupyter Notebook.

## Introduction
For this project, I have analyzed data from Kaggle. This data contains the names, job title, and compensation such as BasePay,OtherPay,Benefits,TotalPay,and TotalBenefitsPay for San Francisco city employees on an annual basis from 2011 to 2014.

This project involves taking messy data, then cleaning it up and doing analysis. Most part of this project is dealing with data cleaning. There are a few specific things what I have done in cleaning data:

  1. Filling in missing values
  2. Correcting erroneous datatype: some object datatype shoudl be numeric.
  3. Normalizing values: convert all values of EmployeeName and JobTitle to uppercase and prepare for future analysis.
  4. Standardizing categories: In many cases where data is collected from users directly – particularly using free text fields – spelling      mistakes, language differences or other factors will result in a given answer being provided in multiple ways. For example, under the JobtTitle column, data inevitably contain multiple spellings of the same job title (e.g. CHIEF OF DEPARTMENT, (FIRE DEPARTMENT), CHIEF, FIRE DEPARTMENT)

## Requirements
* Python3
* Numpy
* Pandas
* Matplotlib
* Seaborn
* Jupyternotebook

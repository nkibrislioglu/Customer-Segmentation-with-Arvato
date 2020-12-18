# Customer Segmentation with Avarto

## Table of Contents
* Libraries
* Project Motivation
* File Descriptions
* Licensing, Authors, and Acknowledgements

## Libraries
The libraries used in this repository are:
* pandas
* numpy
* matplotlib
* seaborn
* sklearn
* xgboost
* collections


## Project Motivation
The research question we pursue is:
 ‘How effectively can a mail order sales company expands its customer base?’.  
 To answer this question, I used two methods: customer segmentation with unsupervised learning and a machine learning model.

### Understanding the data
There are four main and two supplemantary data sets:  
**Udacity_AZDIAS_052018.csv:** Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns). 
**Udacity_CUSTOMERS_052018.csv:** Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns). 
**Udacity_MAILOUT_052018_TRAIN.csv:** Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns). 
**Udacity_MAILOUT_052018_TEST.csv:** Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns). 

Each row of the demographics files represents a single person, but also includes information outside of individuals, including information about their household, building, and neighborhood. The "CUSTOMERS" file contains three extra columns ('CUSTOMER_GROUP', 'ONLINE_PURCHASE', and 'PRODUCT_GROUP'), which provide broad information about the customers depicted in the file. The original "MAILOUT" file included one additional column, "RESPONSE", which indicated whether each recipient became a customer of the company or not. This column enables us to run a supervised learning model.

There are also two supplementary files which includes additional information about features, meaning and their coding.  
**DIAS Information Levels - Attributes 2017.xlsx:** A top-level list of attributes and descriptions, organized by informational category. 
**DIAS Attributes - Values 2017.xlsx:** A a detailed mapping of data values for each feature in alphabetical order.

Under the terms and conditions, I am not allowed to share the data files.

## File Descriptions
There are five jupiter notebooks and two csv files in this repository. Data files were explained under the understanding the data section. File names are:

* Avarto_Project_Workbook.ipynb: Includes data preprocessing, supervised and unsupervised learing codes

* Report.pdf: The report of the findings

* Terms.pdf:  The terms and conditions to use the data sets


## Licensing, Authors, and Acknowledgements
In addition to Udacity's Terms of Use and other policies, your downloading and use of the AZ Direct GmbH data solely for use in the Unsupervised Learning and Bertelsmann Capstone projects are governed by the following additional terms and conditions. The big takeaways:
You agree to AZ Direct GmbH's General Terms provided below and that you only have the right to download and use the AZ Direct GmbH data solely to complete the data mining task which is part of the Unsupervised Learning and Bertelsmann Capstone projects for the Udacity Data Science Nanodegree program.
You are prohibited from using the AZ Direct GmbH data in any other context.
You are also required and hereby represent and warrant that you will delete any and all data you downloaded within 2 weeks after your completion of the Unsupervised Learning and Bertelsmann Capstone projects and the program.
If you do not agree to these additional terms, you will not be allowed to access the data for this project.
The full terms are provided in the workspace below. You will then be asked in the next workspace to agree to these terms before gaining access to the project, which you may also choose to download if you would like to read in full the terms.
These same exact terms are provided in the next workspace, where you will be asked to accept the terms prior to gaining access to the data.
The detailed terms and conditions can be found in the terms file in this repository.

##### Note: This repository is part of Udacity Data Science Nano degree program projects

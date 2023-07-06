# Customer Segmentation Report for Arvato Financial Services

## by Liudmila Danilovskaya 

The goal of this project is to better understand customer's needs and apply tailored marketing campaign.

This is achieved by creating an unsupervised machine learning model to group customers based on their similarities and differences in order to identify segments of the population that form the core customer base for a mail-order sales company in Germany.

The second goal is to created a model to predict which individuals are most likely to respond to a mailout campaign.

## Datasets 

There are four data files associated with this project:

**Udacity_AZDIAS_052018.csv**: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).

**Udacity_CUSTOMERS_052018.csv**: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).

**Udacity_MAILOUT_052018_TRAIN.csv**: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).

**Udacity_MAILOUT_052018_TEST.csv**: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

**DIAS Attributes - Values 2017 (1).xlsx**: Attributes description and values.

## Project structure

+ Data Gathering
+ Data Cleaning
+ Principal Component Analysis
+ Determining the optomal number of clusters
+ Applying clustering to general population
+ Compare customer data to general population
+ Supervised Machine Learning
 

## Installation and running

This project requires Python 3.x and the following Python libraries installed:

+ pandas 1.3.5
+ scikit-learn 1.0.2
+ matplotlib 3.0.3
+ numpy 1.21.6
+ seaborn 0.9.0
+ scipy 1.7.3
+ tqdm 4.64.1
+ openpyxl 3.1.2
+ xgboost 1.6.2

To install all libraries: pip install -r requirements.txt 


## Summary of Findings


The key findings of the analysis are summarized in the blog post:

https://medium.com/@mila.danilovskaya/understanding-your-customers-key-insights-from-arvato-financial-solutions-segmentation-analysis-b1a772ba5a6c


## Acknowledgments

This project was done as the part of Udacity learning. The data is provided by Arvato Financial Services, a Bertelsmann subsidiary.
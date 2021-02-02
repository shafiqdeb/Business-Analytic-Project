# Business Analytic Project
A mini project I did to learn exploratory data analysis and apply machine learning into the dataset.

## Introduction
This mini project aims to analyze a business data from a sport store. This store sells various sport equipments and has been operating since 2013. In early 2019, the manager of the store notice a decline in its customers, so they wanted to know what has been affecting such downturn. The store manager defines that a customer is considered **attrited** when they are have not made any transaction or purchase through the store until the last 6 months from the last available data update.

The dataset used in this project is store transaction data ranging from 2013 to 2019 in `.csv` (comma separated value) format, with the file name `data_retail.csv`. The source of the dataset is availabe [here]( https://dqlab-dataset.s3-ap-southeast-1.amazonaws.com/data_retail.csv).

## Objectives
This mini project is just an exercise to:
1. Learn Exploratory Data Analysis by preparing and visualizing the data.
2. Apply Machine Learning Model to predict customer attrition.

## Contents
### 1. Data Preparation
- Import data
- Remove unnecessary columns
- Data type conversion
- Customer churn categorization

### 2. Data Visualization
- Customer purchase per year
- Transaction count per year
- Average transaction per year for each product
- Proportion churn by product
- Customer distribution by Transaction group
- Customer distribution by Average Transaction amount group

### 3. Data Modelling
- Determine variables
- Split data into Train and Test
- Create and fit model
- Calculate confusion matrix

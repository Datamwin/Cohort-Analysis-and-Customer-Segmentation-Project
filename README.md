# Cohort-Analysis-and-Customer-Segmentation-Project

**Project Overview**

This project aims at calculating the customer retention rate through cohort analysis, and segmenting customers for a UK based online retail company.
Customers are segmented using an unsupervised machine-learning algorithm. The segmentation is based on three metrics - Recency, Frequency and Monetary.
Recommendations are made based on findings from analyzing the segments(clusters)

**Cohort Analysis** 

Cohort means a group of entities with common behaviour or characteristics.

Cohort analysis is a type of behavioural analytics in which entities (in this case consumers ) are grouped based on their shared characteristics.It is basically the description of cohorts.

Cohort analysis could be based on cohort size, behavoir, or time. Time based cohort analysis calculates retention rate which helps make informed product decisions that reduce customer churn and increase revenue. 
Time based cohort analysis measures customer engagement over time.

**Customer segmentation**

Customer segmentation is the act of dividing customers into groups such that each group has similar characteristics.
Customer segmentation could be based on customer location, demographics, or behaviour.

This project is divided into two sections. Whiles section one focuses on cohort analysis , section two focues on customer segmentation.

## Problem Statements

A Retail  Company wants to improve its products, customer relations and maximize sales.

To achieve this, the comapny wants to calculate the percentage of customers it's able to retain in a month.

The company also need to segment it cusromers for target maketting and promotions.


## The project stages are as follows:

**1. Data gathering**

The dataset is from a  Retail Company and can be obtained from the [UCI Machine learning repository](https://archive.ics.uci.edu/ml/datasets/online+retail)

**2. Exploratory Data Analysis and Data Cleaning**

At this stage, the data was explored using descriptive statistics and visualizations.
The quality of the data was ensured by cleaning and removing missing and  negative values of sales and unit price which were  perceived to be returned goods or data entry errors.

**3. Time-based cohort analysis**
This stage provides a solution to the first part of the problem statement.

At this stage, the retention rate for each cohort is calculated and visualized. 


**4. Feature Engineering**

Metrics that represent customers' behaviour were created from the already existing variables.
The metrics include Recency, Frequency and Monetary.
Segmentation will be done using these metrics.

**5. Data preprocessing for modelling**

At this point, the metrics are centred and transformed to enhance KMeans clustering.

**6. Creating clusters using KMeans Algorithm**

This is the modelling stage where an unsupervised machine learning algorithm is implemented to build clusters. 

**7. Analyzing each cluster**

This stage involves analysis of  each cluster to regards Recency Frequency and Monetary value.

**8. Conclusion and Recommendations**

This is the final stage. It comprises the report on the findings from the project and recommendations.

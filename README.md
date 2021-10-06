## Cohort-Analysis-and-Customer-Segmentation-Project

This project aims at calculating customer retention rate through cohort analysis and segmenting customers for an online retail company.
Customers are segmented using an unsupervised machine learning algorithm. The segmentation is based on three metrics - Recency, Frequency and Monetary.
Recomendation are made based on findings from anyzing the segments(clusters)


## The project stages are as follows:

**1. Data gathering**

The dataset is from a  Retail Company and can be obtained from the [UCI Machine learning repository](https://archive.ics.uci.edu/ml/datasets/online+retail)

**2. Exploratory Data Analysis and Data Cleaning**

At this stage, the data was explored using descriptive statistics and visualizations.
The quality of the data was ensured by cleaning and removing missing and  negative values of sales and unit price which were  percieved to be returned goods or data entry error.

**3. Time based cohort analysis**
This stage provides solution to the first part of the problem stament.

At this stage, the retention rate for each cohort is calculated and visualized. 


**4. Feature Engineering**

Metrics that represent customers behaviour were created to from the alresdy existing variables.
The metrics includes Recency,Frequency and Monetary.
Segmentation will be done using these metrics.

**5. Data preprocessing for modelling**

At this point, the metrics are centered and tranformed to enhace KMeans clustering.

**6. Creating clusters using KMeans Algorithm**

This is the modelling stage where an unsupervised machine learning algorithm is implemented to build custers. 

**7. Analyzing each cluster**

This satge involves analysis of  each cluster to regards Recency Frequency and Monetary value.

**8. Conclusion and Recommendations**

This is the final stage. It comprises the report on the the findings from the project and recomendations.

Customer Segmentation Analysis

Objective:
The goal of this project is to perform customer segmentation using clustering techniques and derive actionable insights for marketing and sales strategies.

1. Data Overview
Dataset:
The dataset contains information about customers, including demographic details, education level, occupation, income, and city size.
Exploratory Data Analysis (EDA):
Conducted an exploratory analysis to understand the distribution of various features.
Noted that the dataset is skewed towards:
Male customers.
Single individuals.
Customers with education level at high school.
Skilled employees.
Residents of small cities.
Summary Statistics:
Age is strongly right-skewed, with a mode around 26-27.
Income is slightly right-skewed, with a mode around $100k-$126k USD.
2. Multivariate Analysis
Gender Analysis:
Explored the relationship between gender and other variables.
Noted that single males and non-single females tend to visit the mall more frequently.
Education Analysis:
Analyzed the distribution of education level by gender.
Found that both males and females mostly have an education level at high school.
3. Cluster Modeling
KMeans, MeanShift, and Gaussian Mixture:
Applied KMeans, MeanShift, and Gaussian Mixture Models for customer segmentation.
Conducted silhouette analysis to determine the optimal number of clusters for each model.
Model Evaluation:
Evaluated the performance of each model using average silhouette score.
Identified KMeans as the best-performing model with the highest silhouette score.
4. Further Analysis
Cluster Interpretation:
Analyzed each cluster derived from the KMeans model to understand the characteristics of each segment.
Identified distinct demographics, education levels, occupations, city sizes, age distributions, and income levels for each cluster.
Conclusion:
Customer segmentation analysis using KMeans clustering provides valuable insights into different customer segments. These insights can be leveraged to tailor marketing campaigns, product offerings, and customer experiences to better meet the needs and preferences of diverse customer groups.






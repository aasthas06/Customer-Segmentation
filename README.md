# Customer-Segmentation

## Overview

This project applies unsupervised machine learning techniques to segment customers into distinct groups based on their demographic characteristics and spending behaviour. Using K-Means Clustering, the analysis identifies meaningful customer personas that can help businesses improve marketing strategies, customer targeting, and resource allocation.

## Dataset Features

* Age
* Spending Score
* Marital Status
* Education Status
* Profession
* Work Experience
* Family Size

## Methodology

* Cleaned and preprocessed missing values
* Encoded categorical spending levels into numerical values
* Removed non-interpretable features
* Standardised data using StandardScaler
* Applied the Elbow Method to determine the optimal number of clusters
* Built a K-Means Clustering model
* Visualised customer segments and cluster centroids

## Results

* Identified **5 distinct customer segments**
* Cluster centroids demonstrated strong separation and stability
* Spending behaviour emerged as a stronger differentiator than age

### Customer Segments

* **Primary High-Spenders** – Young and middle-aged customers with high spending behaviour
* **Affluent Seniors** – Older customers with high purchasing power
* **Prudent Youth** – Younger customers with lower spending patterns
* **Frugal Mid-Aged** – Budget-conscious middle-aged customers
* **Economical Seniors** – Older customers with conservative spending habits

## Business Insights

The analysis revealed that customers naturally group into different spending tiers regardless of age. These insights can be used to:

* Improve customer targeting
* Personalise marketing campaigns
* Identify high-value customer groups
* Support data-driven business decisions

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## Key Learning Outcomes

* Data preprocessing and feature engineering
* Customer segmentation techniques
* K-Means Clustering
* The Elbow Method for cluster selection
* Data visualisation and interpretation
* Unsupervised machine learning

## Author

Aastha Singhal

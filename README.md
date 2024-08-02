**Name**: Manne Chakradhar     

**Company**: CODETECH IT SOLUTIONS

**ID**: CT4DA4341

**Domain**: Data Analytics

**Duration**: July 10th - August 10th

**Mentor**: Muzammil Ahmed

# Customer Segmentation Analysis Using k-Means Clustering
Customer Segmentation is the process of dividing the customer base into several groups of individuals that share a similarity in different ways which are relevant to marketing such as gender, age, interests, and miscellaneous spending habits. The customer segmentation technique depends on several key differentiators that divide customers into groups to be targeted. Data related to demographics, geography, economic status, and behavioural patterns are crucial in determining the company's direction towards addressing the various segments.
This project focuses on performing Customer Segment Analysis using unsupervised learning techniques on a given dataset. The goal is to identify distinct customer segments based on their purchasing behaviour, demographics, and other relevant features. This analysis helps in understanding customer preferences and targeting marketing efforts more effectively.

# Overview
While using the k-means clustering algorithm, the first step is to indicate the number of clusters (k) that we wish to produce in the final output. The algorithm starts by selecting k objects from the dataset randomly that will serve as the initial centres for our clusters. These selected objects are the cluster means, also known as centroids. Then, the remaining objects have an assignment of the closest centroid. This centroid is defined by the Euclidean Distance present between the object and the cluster mean. We refer to this step as “cluster assignment”. When the assignment is complete, the algorithm proceeds to calculate the new mean value of each cluster present in the data. After the recalculation of the centres, the observations are checked if they are closer to a different cluster. Using the updated cluster mean, the objects undergo reassignment. This goes on repeatedly through several iterations until the cluster assignments stop altering. The clusters that are present in the current iteration are the same as the ones obtained in the previous iteration.

## K-means Algorithm
We specify the number of clusters that we need to create.
The algorithm selects k objects at random from the dataset. This object is the initial cluster or mean.
The closest centroid obtains the assignment of a new observation. We base this assignment on the Euclidean Distance between the object and the centroid.
k clusters in the data points update the centroid through the calculation of the new mean values present in all the data points of the cluster. The kth cluster’s centroid has a - - Length of p that contains the means of all variables for observations in the kth cluster. We denote the number of variables with p.
Iterative minimization of the total within the sum of squares. Then through the iterative minimization of the total sum of the square, the assignment stop wavering when we - - Achieve maximum iteration. The default value is 10 which the R software uses for the maximum iterations.

# Dataset
The dataset used for this analysis is Malls Customers, which contains information about customer demographics, purchasing behaviour, and other relevant features.
The objective of this project is to segregate customers into specific groups so that the marketing team can target them with products and services tailored to those specific groups.
In this project, we start by cleaning, transforming and performing EDA on the dataset. We then find an optimal number of clusters using the Elbow method and train our KMeans model based on an optimal number of clusters. Lastly, we perform PCA to transform and gain insights from the data.
The dataset contains CustomerID, Gender, Age, Annual Income and Spending Score(1-100). It contains 200 customer details.
- customer_id: a unique ID assigned to the customer.
- gender: gender of the customer (male or female).
- age: age of the customer.
- annual_income: the annual income of customers in thousands of dollars.
- spending_score: the score assigned by the mall based on customer behaviour and spending nature.

## Methodology
### Data Preprocessing:
- Handled missing values and outliers.
- Performed feature scaling and normalization.
- Reduced dimensionality using PCA (if applicable).
  
 ### Clustering:
- Applied K-Means clustering to segment customers into distinct groups.
- Evaluated the optimal number of clusters using the Elbow Method and Silhouette Score.

### Analysis:
- Analyzed each segment to identify key characteristics and behaviours.
- Visualized clusters and their distribution across different features.

## Determining Optimal Clusters
  While working with clusters, you need to specify the number of clusters to use. You would like to utilize the optimal number of clusters. To help you in 
  determining the optimal clusters, there are three popular methods –
  Elbow method The main goal behind cluster partitioning methods like k-means is to define the clusters such that the intra-cluster variation stays minimal.

# Installation
## Jupyter Notebook:
Provides an interactive environment for running Python code and documenting the analysis process. 
## Libraries:
Key libraries such as Pandas (for data manipulation), Matplotlib and Seaborn (for data visualization), and NumPy (for numerical operations) are utilized.

## Tools and Libraries:
The tools used in this project include:
Python - This was needed to conduct Data Quality Assessment and also for Data Cleaning processes. With Python libraries pandas, matplotlib, and seaborn exploratory data analysis of the datasets and gaining useful insights from the data was possible.

# Results and Findings
 We have Categorised the data using k-means clustering and plotted the clusters and their Centroids into 5 clusters.
 Using KMeans Clustering by the data analysis, the above is the visualisation of all 5 clusters based on Annual Income and Spending Score





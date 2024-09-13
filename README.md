# Mall Customer Segmentation using K-Means Clustering

This project is a part of the **Mall Customer Segmentation Data** competition held on Kaggle. The main objective is to segment customers into distinct groups based on their purchasing behavior, which can provide valuable insights into customer preferences and help the company in tailoring marketing strategies and increasing revenue.

## Overview

Customer segmentation is a powerful approach for understanding customer heterogeneity. One of the widely used techniques for segmentation is **K-means clustering**, an unsupervised learning algorithm that partitions data into non-overlapping groups or clusters. This project applies K-means clustering to the customer data provided in the competition to discover distinct customer segments.

The results of the segmentation can help companies:
- Understand the diverse needs and preferences of different customer groups.
- Design targeted marketing strategies.
- Improve customer satisfaction and retention.
- Enhance overall revenue by focusing on high-value customer segments.

## Table of Contents

- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Modeling Approach](#modeling-approach)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [References](#references)

## Dataset

The dataset contains customer information, including:
- **Customer ID**: A unique ID for each customer.
- **Gender**: Gender of the customer.
- **Age**: Age of the customer.
- **Annual Income**: Annual income of the customer.
- **Spending Score**: A score assigned by the mall based on customer behavior and spending habits.

The goal is to identify meaningful customer segments that share similar characteristics based on these features.

## Project Workflow

1. **Data Preprocessing**:
   - Handle missing or incorrect data.
   - Feature scaling using Standardization to normalize the features.
   
2. **Exploratory Data Analysis (EDA)**:
   - Analyze and visualize the distribution of customers based on gender, age, income, and spending score.
   - Correlation analysis to understand relationships between variables.
   
3. **K-Means Clustering**:
   - Implement the K-means clustering algorithm using **Scikit-learn**.
   - Choose the optimal number of clusters using the **Elbow Method** and **Silhouette Score**.
   
4. **Cluster Analysis**:
   - Visualize customer segments using 2D and 3D plots.
   - Provide insights into the characteristics of each segment.
   
5. **Model Evaluation**:
   - Evaluate the clusters formed using the silhouette score.
   - Interpret the results and suggest business strategies based on customer segments.

## Modeling Approach

- **K-Means Clustering**:
  K-means aims to group customers based on the similarity in their demographic and behavioral features. The algorithm minimizes the within-cluster variance and maximizes the between-cluster variance.

  Key steps:
  1. Choose the number of clusters (K).
  2. Assign each customer to the nearest cluster center.
  3. Recalculate the cluster centroids until convergence.

  For more details on the algorithm, refer to the [Wikipedia article](https://en.wikipedia.org/wiki/K-means_clustering).

## Results

The optimal number of customer segments was found to be `K = X` using the Elbow Method and Silhouette Score. The characteristics of each customer segment were as follows:
- **Cluster 1**: (Description of the segment, such as high-income, low-spending customers).
- **Cluster 2**: (Description of another segment).
- ...

These insights can help the mall tailor its marketing strategies to each customer segment, enhancing customer satisfaction and increasing revenue.

## Technologies Used

- **Python**: Programming language for data analysis and modeling.
- **Pandas**: For data manipulation and preprocessing.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Scikit-learn**: For implementing K-means clustering.
- **Jupyter Notebook**: For developing and presenting the project.

## References

- [K-means Clustering on Wikipedia](https://en.wikipedia.org/wiki/K-means_clustering)
- [Scikit-learn K-means Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)

---

Feel free to contribute, raise issues, or suggest improvements to this project. 

**Author**: [Your Name]

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
  
  ![image](https://github.com/user-attachments/assets/cb45717d-df4b-4039-9386-c5980221138c)

  Key steps:
  1. Choose the number of clusters (K).
  2. Assign each customer to the nearest cluster center.
  3. Recalculate the cluster centroids until convergence.


## Results

The optimal number of customer segments was found to be `K = X` using the Elbow Method and Silhouette Score. The characteristics of each customer segment were as follows:
- **Cluster 1**: (Description of the segment, such as high-income, low-spending customers).
- **Cluster 2**: (Description of another segment).
  ![image](https://github.com/user-attachments/assets/04bbc386-5a46-468c-bd8c-d4a8596630b9)
  ![image](https://github.com/user-attachments/assets/ac3c26d9-59e5-4368-95bd-5e740c44f66e)
  ![image](https://github.com/user-attachments/assets/1f1c1c95-6285-4771-9e64-26e07006f728)
- These insights can help the mall tailor its marketing strategies to each customer segment, enhancing customer satisfaction and increasing revenue.

## Technologies Used

- **Python**: Programming language for data analysis and modeling.
- **Pandas**: For data manipulation and preprocessing.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Scikit-learn**: For implementing K-means clustering.
- **Jupyter Notebook**: For developing and presenting the project.

## Clustering on 3D data

- **Number of customer in 1st group = 24**
- They are = [129 131 135 137 139 141 145 147 149 151 153 155 157 159 161 163 165 167 169 171 173 175 177 179]

  
- **Number of customer in 2nd group = 29**
- They are = [ 47  51  55  56  57  60  67  72  77  78  80  82  84  86  90  93  94  97 99 102 105 108 113 118 119 120 122 123 127]

  
- **Number of customer in 3rd group = 28**
- They are = [124 126 128 130 132 134 136 138 140 142 144 146 148 150 152 154 156 158 160 162 164 166 168 170 172 174 176 178]

  
- **Number of customer in 4th group = 22**
- They are = [ 2  4  6  8 10 12 14 16 18 20 22 24 26 28 30 32 34 36 38 40 42 46]

  
- **Number of customer in 5th group = 12**
- They are = [ 3  7  9 11 13 15 23 25 31 33 35 37]

![image](https://github.com/user-attachments/assets/e865d1fc-91ad-4365-b360-a076970accc6)

![image](https://github.com/user-attachments/assets/d2603252-ec8c-4982-9d9f-72108ce0ffbe)




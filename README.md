# 🛍️ Customer Segmentation Analysis using K-Means Clustering

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen)

This project is part of the **Mall Customer Segmentation Data** competition held on Kaggle. The goal is to use K-Means clustering to segment customers into distinct groups based on their purchasing behavior, helping to derive insights that can boost revenue by designing effective marketing strategies.

## 📊 Project Overview

Customer segmentation allows businesses to divide their customer base into distinct groups based on specific traits such as buying behavior. This project utilizes **K-Means Clustering**, an unsupervised learning algorithm, to segment customers into meaningful groups, enabling the company to tailor its marketing strategies.

The project covers:
- **Data Cleaning & Preprocessing**
- **Exploratory Data Analysis (EDA)**
- **K-Means Clustering Implementation**
- **Cluster Analysis & Visualization**

## 🚀 Features
- **Data Preprocessing**: Cleaning the dataset and scaling features.
- **Clustering Analysis**: Apply K-means clustering and determine optimal clusters using the Elbow method and Silhouette Score.
- **Visualizations**: 3D and 2D interactive visualizations for customer clusters.
- **Insights**: Actionable insights on customer segments for targeted marketing.

## 📁 Dataset

The dataset contains information about:
- **Customer ID**: Unique identifier for each customer.
- **Gender**: Gender of the customer.
- **Age**: Age of the customer.
- **Annual Income**: Annual income of the customer in thousands of dollars.
- **Spending Score**: A score between 1-100 assigned by the mall based on customer spending behavior.

## 📊 Workflow

### 1. **Data Preprocessing**
- **Handling Missing Data**: Checked for missing or incorrect data.
- **Feature Scaling**: Applied standardization to normalize features like income and spending score.

### 2. **Exploratory Data Analysis (EDA)**
- Visualized distributions of age, income, and spending.
- Analyzed correlations between features.
  
### 3. **K-Means Clustering**
- **Elbow Method** and **Silhouette Score** were used to determine the optimal number of clusters.
- Applied K-Means to form customer clusters.

### 4. **Cluster Analysis**
- Visualized customer clusters using 2D and 3D scatter plots.
- Derived insights based on cluster characteristics for business strategies.

### 5. **Model Evaluation**
- Used the **silhouette score** to evaluate the quality of clustering.
- Provided recommendations based on the insights from each cluster.

## 📦 Installation and Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/customer-segmentation-analysis.git
   cd customer-segmentation-analysis

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

   
## 🧪 Modeling Approach
**K-Means Clustering Algorithm**
- K-Means is used to segment customers into clusters by minimizing the distance between each customer and their assigned cluster center.

  **Steps involved:**
  1. Select the number of clusters 𝐾.
  2. Assign each customer to the nearest cluster center.
  3. Recompute the centers of each cluster until convergence.
  4. K-means aims to group customers based on the similarity in their demographic and behavioral features. The algorithm minimizes the within-cluster variance and maximizes the between-cluster variance.
  
  ![image](https://github.com/user-attachments/assets/cb45717d-df4b-4039-9386-c5980221138c)

## 📊 Results

The optimal number of customer segments was found to be `K = X` using the Elbow Method and Silhouette Score. The characteristics of each customer segment were as follows:
- **Cluster 1**: (Description of the segment, such as high-income, low-spending customers).
- **Cluster 2**: (Description of another segment).
<img src="https://github.com/user-attachments/assets/04bbc386-5a46-468c-bd8c-d4a8596630b9" alt="image 1" width="400">
<img src="https://github.com/user-attachments/assets/ac3c26d9-59e5-4368-95bd-5e740c44f66e" alt="image 2" width="400">
<img src="https://github.com/user-attachments/assets/1f1c1c95-6285-4771-9e64-26e07006f728" alt="image 3" width="400">
<img src="https://github.com/user-attachments/assets/be04195d-5fd2-4608-a720-6e0554c85cfb" alt="image description" width="400">

- These insights can help the mall tailor its marketing strategies to each customer segment, enhancing customer satisfaction and increasing revenue.

## Technologies Used

- **Python**: Programming language for data analysis and modeling.
- **Pandas**: For data manipulation and preprocessing.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Scikit-learn**: For implementing K-means clustering.
- **Jupyter Notebook**: For developing and presenting the project.

## 📈 Clustering on 3D Data
- After clustering the data, the following customer counts were obtained for each cluster:
  1. Cluster 1: 24 customers [129, 131, 135, ...]
  2. Cluster 2: 29 customers [47, 51, 55, ...]
  3. Cluster 3: 28 customers [124, 126, 128, ...]
  4. Cluster 4: 22 customers [2, 4, 6, ...]
  5. Cluster 5: 12 customers [3, 7, 9, ...]

- 
   <img src="https://github.com/user-attachments/assets/e865d1fc-91ad-4365-b360-a076970accc6" alt="image 22" width="500">
   <img src="https://github.com/user-attachments/assets/d2603252-ec8c-4982-9d9f-72108ce0ffbe" alt="image 23" width="800">

## 🤝 Contributions
**Contributions are welcome! Feel free to open an issue or submit a pull request with improvements or suggestions.**




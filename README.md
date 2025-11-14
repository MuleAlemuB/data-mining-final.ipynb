# Mall Customer Segmentation

## Project Overview
This project performs customer segmentation on a mall's customer dataset to identify distinct groups based on their spending behavior and annual income. The analysis helps in understanding customer profiles, which can guide marketing strategies and business decisions.

The dataset used is `Mall_Customers.csv`, which contains attributes such as CustomerID, Gender, Age, Annual Income (k$), and Spending Score (1-100).

## Objectives
- Segment customers into meaningful groups using **K-Means Clustering**.
- Visualize clusters and understand patterns in customer behavior.
- Identify key insights such as high-value customers or low-spending groups.
- Save the processed data and trained model for further analysis or deployment.

## Key Steps
1. **Data Loading** – Import the dataset into a Pandas DataFrame.
2. **Exploratory Data Analysis (EDA)** – Visualize distributions, correlations, and relationships.
3. **Data Preprocessing** – Handle missing values, encode categorical variables, and prepare features.
4. **Feature Selection** – Use relevant features (`Annual Income`, `Spending Score`) for clustering.
5. **Modeling** – Apply **K-Means Clustering** to segment customers.
6. **Cluster Evaluation** – Analyze **Inertia** and **Silhouette Score** to determine optimal clusters.
7. **Visualization** – Plot clusters and centroids for clear interpretation.
8. **Export Results** – Save clustered data as `Mall_Customers_Segmented.csv` and trained model as `kmeans_mall_model.pkl`.

## Key Results
- **Total Clusters Formed:** 5  
- **Inertia (Sum of squared distances):** 169.89  
- **Silhouette Score:** 0.3883
##cluster_summary
 

    
  


  

    
  

  

# Customer Segmentation Using Clustering

Customer segmentation for a supermarket mall using unsupervised machine learning. KMeans and Agglomerative Clustering are applied to customer data (age, gender, income, spending score) to identify distinct groups and analyse purchasing patterns, helping businesses design targeted marketing strategies.

This project is implemented in Python using Google Colab.

## Methods
- K-Means Clustering
- Agglomerative (Hierarchical) Clustering

## Requirements
- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn
- scipy

## Notebook Structure
1. Setup — Install & Import Libraries
2. Data Loading & EDA (distributions, correlation heatmap, pairplot)
3. Data Preprocessing (feature selection, standardisation)
4. Optimal Number of Clusters (Elbow Method + Silhouette Score sweep)
5. KMeans Clustering (multi-view scatter plots)
6. Agglomerative Clustering (dendrogram + scatter plots)
7. Evaluation Metrics (Silhouette, Davies-Bouldin, Calinski-Harabasz)
8. Cluster Profiling & Business Insights (segment labels, annotated plots)
9. Conclusion

## Results
KMeans (k=5) outperforms Agglomerative Clustering on all evaluation metrics. Five distinct customer segments are identified: VIP, Conservative, Impulsive, Careful, and Standard.

## Dataset
[Mall Customers Dataset — Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python/data)

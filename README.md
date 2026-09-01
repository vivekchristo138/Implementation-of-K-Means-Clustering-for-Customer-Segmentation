# Implementation-of-K-Means-Clustering-for-Customer-Segmentation

## AIM:
To write a program to implement the K Means Clustering for Customer Segmentation.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Load the customer dataset and select the required customer features.
2. Choose the number of clusters (K) and initialize the cluster centroids.
3. Apply K-Means Clustering by assigning customers to the nearest centroid and updating centroids repeatedly.
4. Display the customer segments and visualize the clusters using a graph.

## Program:
```
/*
Program to implement the K Means Clustering for Customer Segmentation.
Developed by: Vivek Christo A
Register Number: 212225040497


import pandas as pd
import matplotlib.pyplot as plt
from sklearn.cluster import KMeans
data = pd.read_csv(r"C:\Users\acer\Downloads\Mall_Customers (1).csv")
X = data.iloc[:, [3, 4]].values
kmeans = KMeans(n_clusters=5, random_state=0)
y_kmeans = kmeans.fit_predict(X)
plt.scatter(X[:, 0], X[:, 1], c=y_kmeans, s=100)
plt.scatter(kmeans.cluster_centers_[:, 0],
            kmeans.cluster_centers_[:, 1],
            s=200,
            marker='X')
plt.xlabel("Annual Income")
plt.ylabel("Spending Score")
plt.title("Customer Segmentation using K-Means")
plt.show()

*/

```

## Output:

<img width="795" height="492" alt="image" src="https://github.com/user-attachments/assets/bee4f5bd-82ad-4814-922a-9c7e16d019ac" />


## Result:
Thus the program to implement the K Means Clustering for Customer Segmentation is written and verified using python programming.

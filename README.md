# 🌸 Hierarchical Clustering on Iris Dataset

---

# 📌 Project Overview

This project demonstrates the use of **Hierarchical Clustering**, an unsupervised machine learning technique used to discover hidden patterns in data without using labels.

The goal of this project is to apply hierarchical clustering to the **Iris dataset** and analyze how the algorithm groups similar data points into clusters.

Hierarchical clustering builds a **tree-like structure of clusters**, allowing us to observe relationships between data points at different levels of similarity. The results are visualized using a **dendrogram**, which helps understand how clusters are formed step by step.

This project helps in understanding how clustering algorithms organize data and how hierarchical relationships between clusters can be visualized.

---

# 📂 Dataset

## Iris Dataset

The **Iris dataset** is one of the most commonly used datasets in machine learning for pattern recognition and clustering.

Dataset characteristics:

- **150 samples**
- **3 species of iris flowers**
  - Setosa
  - Versicolor
  - Virginica

Each sample contains **four numerical features**:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Although the dataset contains labels for the species, the clustering algorithm **does not use these labels**, because clustering is an **unsupervised learning task**.

The purpose of the algorithm is to discover the natural grouping of samples based only on their features.

---

# ⚙️ Hierarchical Clustering

Hierarchical clustering is a method of cluster analysis that builds a **hierarchy of clusters**.

Instead of assigning data points directly to clusters, the algorithm gradually merges clusters based on similarity.

There are two main types of hierarchical clustering:

- **Agglomerative (Bottom-Up)**
- **Divisive (Top-Down)**

In this project, **Agglomerative Hierarchical Clustering** is used.

---

# 🔍 Working of the Algorithm

Hierarchical clustering works through the following steps:

1. Each data point starts as its own cluster.
2. The algorithm calculates the distance between all clusters.
3. The two closest clusters are merged.
4. The distance matrix is updated.
5. Steps 2–4 repeat until all data points form a single cluster.

The clustering process is represented visually using a **dendrogram**.

A dendrogram shows:

- Which clusters merge
- At what distance they merge
- The hierarchy of clusters

---

# 📊 Dendrogram Visualization

A **dendrogram** is a tree-like diagram used to visualize the hierarchical relationships between clusters.

Important aspects of a dendrogram:

- The **vertical axis** represents the distance between clusters.
- The **horizontal axis** represents the data points.
- Clusters that merge at **lower distances** are more similar.

By cutting the dendrogram at a certain height, we can determine the **optimal number of clusters**.

---

# 📈 Observations

When hierarchical clustering is applied to the Iris dataset:

- Some groups of samples naturally form clusters.
- **Setosa samples tend to form a clearly separate cluster.**
- **Versicolor and Virginica show partial overlap**, which is expected due to similar feature values.

The dendrogram helps visualize these relationships clearly.

---

# 🛠 Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

# 📊 Output

The project generates:

- A **dendrogram** showing hierarchical cluster relationships
- Visualization of how Iris samples group together based on similarity

These visualizations help in understanding the cluster formation process.

---

# 🎯 Conclusion

Hierarchical clustering is a powerful technique for exploring the structure of data and understanding relationships between data points.

Key takeaways from this project:

- Hierarchical clustering builds clusters step by step.
- The dendrogram provides a clear visualization of cluster hierarchy.
- The algorithm successfully groups similar Iris samples together.
- It is especially useful for **small to medium-sized datasets where cluster relationships need to be analyzed visually**.

---

## 👩‍💻 Author
**Vaishnavi Rathi**

---

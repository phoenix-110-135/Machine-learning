# ✨ Welcome to the Unsupervised Learning Projects! ✨

This repository contains advanced projects focused on **Unsupervised Learning**, specifically **Clustering**, using Python and popular libraries like Scikit-learn, Pandas, Matplotlib, and Seaborn. We explore data patterns without prior labels! 🚀

---

## 📁 Project Structure

- `unsupervise/`: This folder likely contains helper scripts, datasets, or intermediate files used in the projects.
  - *(Specific contents of this folder would be detailed here if known)*

---

## 📚 Project 1: Mall Customers Clustering 🛍️

This project delves into customer segmentation using unsupervised learning techniques on the 'Mall Customers' dataset.

### 🎯 Goals:
- Analyze customer demographics and spending habits.
- Segment customers into distinct groups for targeted marketing.
- Explore various clustering algorithms.

###  algorithms Used:
- **K-Means Clustering**: A popular algorithm for partitioning data into 'k' clusters.
- **Gaussian Mixture Models (GMM)**: A probabilistic model assuming data points are generated from a mixture of Gaussian distributions.
- **DBSCAN**: Density-Based Spatial Clustering of Applications with Noise, good for irregular shapes.
- **Agglomerative Hierarchical Clustering**: Builds a hierarchy of clusters.

### 📊 Key Features:
- **Exploratory Data Analysis (EDA)**: Pair plots and correlation heatmaps to understand data relationships.
- **Preprocessing**: Data scaling using `StandardScaler`.
- **Dimensionality Reduction**: PCA to visualize in 2D.
- **Model Evaluation**: Silhouette Score to compare clustering performance.
- **Visualizations**: Interactive 2D PCA plots, 3D plots, and comparison heatmaps.

---

## 🌸 Project 2: Iris Flower Clustering 🌷

A classic machine learning dataset, 'Iris', is used here to demonstrate K-Means clustering and compare its results against true labels.

### 🎯 Goals:
- Cluster Iris flowers based on their sepal and petal measurements.
- Evaluate the performance of K-Means against known species.

### 💡 Core Algorithm:
- **K-Means Clustering**: Applied to group the Iris flowers.

### 🌟 Key Features:
- **Dataset**: The well-known Iris dataset.
- **EDA**: Pair plots with true labels and correlation heatmap.
- **Preprocessing**: Data scaling.
- **Optimal K Determination**: Using the Elbow Method.
- **Visualizations**:
    - 2D PCA scatter plot colored by predicted cluster.
    - 3D plot of clusters.
    - **Confusion Matrix Heatmap**: Comparing predicted clusters with true Iris species.
    - Distribution of distances from cluster centers.
- **Center Analysis**: Displaying cluster centers in the original feature space.

---


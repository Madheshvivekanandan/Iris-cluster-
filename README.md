# K-Means Clustering on the Iris Dataset

This project demonstrates the implementation of the K-means clustering algorithm on the Iris dataset, a popular dataset in machine learning. The dataset consists of measurements of sepal length, sepal width, petal length, and petal width for three species of Iris flowers.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Visualization](#visualization)
- [Results](#results)

---

## Project Overview

The goal of this project is to:
1. Perform clustering on the Iris dataset using the K-means algorithm.
2. Visualize the clusters in both 3D and 4D.
3. Evaluate the quality of clustering using metrics like inertia and silhouette score.

---

## Installation

To run this project, ensure you have the following installed:

- Python 3.8+
- Required libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

You can install the required libraries using:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```
## Usage

1. Clone this repository:
    ```bash
    git clone https://github.com/Madheshvivekanandan/Iris-cluster-.git
    cd kmeans-iris-clustering
    ```
2. Run the script:
    ```bash
    python kmeans_clustering.py
    ```

3. The script will:
    - Load and preprocess the Iris dataset.
    - Perform K-means clustering with 3 clusters.
    - Generate and save visualizations.

---

## Visualization

### 3D Visualization
A 3D scatter plot is generated with three features plotted along the axes, and clusters are distinguished by colors.

### 4D Visualization
A color-coded 3D scatter plot uses the fourth feature as the color gradient, effectively displaying 4 dimensions.

### Pairplot
A pairplot of all features provides insights into the clustering results and feature relationships.

---

## Results

- **Cluster Inertia**: The total within-cluster sum of squares (lower is better).
- **Cluster Visualization**: Centroids and data points are plotted in the generated visualizations.
- **Metrics**:
    - Inertia Score
    - Silhouette Score (if computed)

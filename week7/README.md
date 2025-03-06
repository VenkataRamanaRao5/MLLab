# Lab 7.1: Clustering Algorithms

### Objective
To implement and compare clustering techniques (K-Means, K-Median, K-Mode, K-Medoids) using Python.

### Suggested Datasets
- **Iris Dataset** (for numerical data)
- **Mall Customer Segmentation Dataset** (Income vs Spending Score)
- **Mushroom Dataset** (for categorical data with K-Mode)

### Steps:

#### 1. Load and Preprocess the Data
- Use `pandas` to load a dataset.
- Normalize numerical data using `StandardScaler` or `MinMaxScaler`.

#### 2. Apply K-Means Clustering
- Use `KMeans` from `sklearn.cluster`.
- Set different values for `k` and observe cluster assignments.

#### 3. Apply K-Median Clustering
- Use `kmedoids` from `sklearn_extra.cluster`.
- Compare results with K-Means.

#### 4. Apply K-Mode Clustering (For Categorical Data)
- Use `kmodes.KModes` from `kmodes` library.
- Cluster categorical data and analyze differences.

#### 5. Find how to measure clustering performance

# Lab 7.2: Radial Basis Function (RBF) Network

### Objective
To implement an RBF network for classification using Python.

### Suggested Datasets
- **Iris Dataset** (Multiclass classification)
- **Synthetic Gaussian Dataset** (For better understanding)

### Steps

#### 1. Load and Preprocess Data
- Use `sklearn.datasets.load_iris` or generate synthetic data.

#### 2. Define RBF Kernel (Gaussian)
- Implement the Gaussian basis function

#### 3. Train an RBF Network
- Use `scikit-learn`’s `RBFKernel` or manually implement an RBF network.

#### 4. Compare with Other Known Classifiers
- Compare with models like Logistic Regression or SVM.

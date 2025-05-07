# Customer Segmentation using K-Means Clustering

This project demonstrates unsupervised learning using the **K-Means** clustering algorithm to segment mall customers based on their annual income and spending score.

## 📊 Dataset

- **File**: `Mall_Customers.csv`
- **Features used**: 
  - Annual Income
  - Spending Score
- Non-numeric features (`CustomerID`, `Gender`) were excluded from clustering.

## 🔧 What This Project Does

1. **Loads and preprocesses** the dataset
2. **Scales** numerical features using `StandardScaler`
3. **Uses PCA** for 2D visualization of high-dimensional data
4. **Fits K-Means** to find customer clusters
5. **Uses Elbow Method** to determine the optimal number of clusters
6. **Evaluates clustering** using Silhouette Score
7. **Visualizes clusters** with color-coded plots

## 📈 Output

- Elbow plot to choose `k`
- Silhouette Score for clustering quality
- 2D scatter plot of clusters (via PCA)

## 🛠 Requirements

- Python 3.x
- scikit-learn
- pandas
- matplotlib
- numpy

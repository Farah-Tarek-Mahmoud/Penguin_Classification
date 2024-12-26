# Penguins Clustering Project

This project utilizes clustering techniques on the Palmer Penguins dataset to group penguins based on key features. Methods include K-Means and Hierarchical Clustering, supported by robust preprocessing, visualization, and evaluation.

## Workflow

### 1. **Data Preparation**
- Loaded and explored the dataset (`penguins.csv`).
- Handled missing values by removing incomplete rows.
- Encoded categorical variables and standardized numerical features.

### 2. **Exploratory Data Analysis (EDA)**
- Visualized feature relationships using scatter plots, pair plots, and heatmaps.

### 3. **Clustering Techniques**
- **K-Means Clustering**:
  - Determined optimal clusters using the Elbow Method.
  - Applied clustering with 3 and 4 clusters.
  - Visualized and summarized cluster characteristics.
- **Hierarchical Clustering**:
  - Created dendrograms using Ward's linkage.
  - Applied Agglomerative Clustering with 4 clusters.
  - Visualized hierarchical clusters.

### 4. **Dimensionality Reduction**
- Performed PCA to reduce dimensionality while retaining significant variance.
- Visualized clusters in PCA-reduced feature space.

### 5. **Evaluation Metrics**
- Assessed clustering quality using:
  - Silhouette Score
  - Calinski-Harabasz Index
  - Davies-Bouldin Index

## Tools and Techniques
- **Libraries**: pandas, matplotlib, seaborn, scikit-learn, scipy
- **Methods**: K-Means, Agglomerative Clustering, PCA

## Key Results
- Successfully clustered penguins into distinct groups using both K-Means and Hierarchical Clustering.
- PCA enabled effective visualization of clusters in reduced dimensions.
- Metrics confirmed the validity of clustering outcomes.

# 🎓 Student Retention Analysis and Risk Clustering

This project involves a comprehensive data analysis and unsupervised machine learning (clustering) effort aimed at identifying and segmenting university students based on their dropout risk and related academic and personal factors.

The primary goal is to define clear profiles of the student population. This segmentation can help the university administration develop targeted support and student retention strategies.

## 🚀 Key Project Components

* **Data Analysis (EDA):** Detailed Exploratory Data Analysis to understand variable distributions, relationships, and identify high-risk groups.
* **Data Preprocessing:** Handling of missing values (using advanced imputation techniques), standardization of numerical data, One-Hot Encoding for categorical features, and calculation of a Gower distance matrix for mixed-data clustering.
* **Dimensionality Reduction:** Application of **PCA**, **t-SNE**, and **UMAP** for data projection and visualization in 2D/3D space.
* **Clustering:** Implementation and evaluation of multiple clustering algorithms (K-Means, Hierarchical Clustering, HDBSCAN) to find the optimal number of student groups.

## 💾 Dataset

* **File:** `university_student_retention_dataset_2134.csv`
* **Description:** Contains data on 2,134 students, including demographics, academic performance (GPA, attendance), financial aid, health status, and dropout status/cause.

## ⚙️ Technologies and Libraries

The project is implemented in a **Jupyter Notebook** and utilizes a comprehensive stack of Python libraries:

| Domain | Key Libraries |
| :--- | :--- |
| **Data Handling** | `Pandas`, `NumPy` |
| **Visualization** | `Matplotlib`, `Seaborn`, `Plotly` |
| **Preprocessing/Imputation** | `StandardScaler`, `IterativeImputer` |
| **Dimensionality Reduction** | `PCA`, `t-SNE`, `UMAP` |
| **Clustering** | `KMeans`, `AgglomerativeClustering`, `HDBSCAN` |
| **Evaluation** | `Silhouette Score`, `Davies-Bouldin Score` |
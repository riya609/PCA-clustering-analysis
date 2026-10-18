# 📊 PCA & Unsupervised Clustering Analysis

### Discovering Patterns in High-Dimensional Data Using Python

An exploratory machine learning project demonstrating dimensionality reduction and unsupervised clustering using Principal Component Analysis (PCA), K-Means, Hierarchical Clustering, and DBSCAN.

## 📌 Project Overview

This project explores patterns in the **Wisconsin Diagnostic Breast Cancer dataset**, which contains 569 samples and 30 numerical features computed from breast cancer cell nuclei images.

PCA is used to reduce the dimensionality of the feature space, while unsupervised clustering algorithms identify groups in the data without using diagnosis labels during cluster formation.

## ✨ Key Features

- **Data Standardization:** Prepare numerical features for PCA and distance-based clustering.
- **Principal Component Analysis (PCA):** Reduce dimensionality and explore explained variance.
- **Explained Variance Analysis:** Use a scree plot to understand how much variance each principal component captures.
- **K-Means Clustering:** Explore cluster assignments and evaluate candidate cluster counts.
- **Hierarchical Clustering:** Investigate nested relationships among observations.
- **DBSCAN:** Identify density-based clusters and potential noise points.
- **Cluster Evaluation:** Use silhouette scores where applicable.
- **Visualizations:** Explore cluster projections in 2D and 3D.

## 🛠️ Technology Stack

- Python
- Jupyter Notebook
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Plotly

## 📂 Project Structure

```text
pca-clustering-analysis/
├── .gitignore
└── pca-clustering-project/
    ├── PCA_Clustering_Analysis.ipynb
    ├── PCA_Clustering_Analysis.html
    ├── README.md
    ├── requirements.txt
    └── reports/
        └── pca_3d_interactive.html
```

## 🚀 Getting Started

### Prerequisites

- Python 3
- Visual Studio Code
- Python and Jupyter extensions

### 1. Clone the repository

```bash
git clone https://github.com/riya609/PCA-clustering-analysis.git
cd PCA-clustering-analysis
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

### 3. Install dependencies

On Windows PowerShell, from the repository root:

```powershell
.\.venv\Scripts\python.exe -m pip install -r .\pca-clustering-project\requirements.txt
```

### 4. Open the notebook

Open `pca-clustering-project/PCA_Clustering_Analysis.ipynb` in VS Code.

Select the `.venv` Python environment as the notebook kernel, then choose **Run All**.

## 📈 Expected Analysis Outputs

The notebook is designed to explore:

- PCA explained-variance and scree plots
- Two-dimensional and three-dimensional cluster visualizations
- K-Means cluster evaluation using the Elbow Method and silhouette scores, where implemented
- Hierarchical clustering and DBSCAN results
- Comparative interpretation of unsupervised clustering patterns

Actual outputs depend on the executed notebook cells and selected parameters.

## 🔬 Methodology

1. Load and prepare the numerical dataset.
2. Standardize features before dimensionality reduction and distance-based analysis, as appropriate.
3. Apply PCA and examine explained variance.
4. Fit and compare unsupervised clustering algorithms.
5. Evaluate cluster quality using suitable metrics.
6. Visualize and interpret the discovered patterns.

**Important:** Diagnosis labels should not be used to fit unsupervised clusters if the objective is to evaluate clustering without supervision. Any comparison with known labels should be performed separately after clustering.

## ⚠️ Limitations

- Clusters do not automatically correspond to clinically meaningful groups.
- Results depend on feature scaling, PCA choices, algorithm parameters, and evaluation metrics.
- Silhouette scores may not be informative for every clustering method or cluster structure.
- This is an educational data analysis project, not a clinical diagnostic tool.

## 👩‍💻 Author

**Riya Maheshwari**  
B.Tech — Computer Science and Engineering (Data Science)

GitHub: [riya609](https://github.com/riya609)

---

*Built to explore dimensionality reduction, unsupervised machine learning, and data visualization using Python.*
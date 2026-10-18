# Dimensionality Reduction & Unsupervised Clustering (Breast Cancer Wisconsin, 30-D)

Notebook: `PCA_Clustering_Analysis.ipynb` (outputs and plots embedded). HTML copy: `PCA_Clustering_Analysis.html`.
Interactive 3D PCA plot (opens in any browser): `reports/pca_3d_interactive.html`.

Covers: standardisation, PCA (scree, cumulative variance, Kaiser, parallel analysis, loadings, biplot, reconstruction error),
K-Means (elbow, silhouette, gap statistic, Calinski-Harabasz, Davies-Bouldin, knife plots, bootstrap stability),
Hierarchical/Ward (dendrogram, cophenetic correlation), DBSCAN (k-distance plot, grid search),
2D Seaborn + 3D Plotly/Matplotlib projections, method comparison, PCA-vs-raw ablation, cluster profiling.
Diagnosis labels are never used for fitting; only for validation at the end.

## Run
```bash
pip install -r requirements.txt
jupyter notebook PCA_Clustering_Analysis.ipynb   # Kernel > Restart & Run All
```
Dataset ships with scikit-learn (no download). Seed fixed at 42.
Note: GitHub does not render Plotly's interactive widget; the notebook also contains a static 3D plot that renders everywhere.

# Comprehensive_ML_Pipeline_Iris
Comprehensive Machine Learning Pipeline: From PCA to Predictive Modeling

An end-to-end machine learning project demonstrating dimensionality reduction, classification, unsupervised clustering, and regression analysis.

Project Overview:
  This repository contains a full machine learning workflow applied to extended biological and environmental datasets. It showcases the ability to handle both supervised and unsupervised learning tasks, extracting meaningful patterns from multi-dimensional data.

Technology Stack:
  Language: Python
  Machine Learning: scikit-learn, statsmodels (OLS Regression)
  Data Processing: pandas, numpy
  Visualization: matplotlib, seaborn (Heatmaps, Scatter plots with LOESS)
  
Core Modules & Implementations:
  1.Dimensionality Reduction (PCA)
    Applied StandardScaler to ensure all 7 features contribute equally by transforming them to zero mean and unit variance.
    Implemented Principal Component Analysis (PCA) to reduce data from 7 features to 2 principal components, retaining high cumulative explained variance.
    Evaluated compactness using Reconstruction Error (MSE).
  2.Supervised Learning: Classification
    Conducted a 70/30 train-test split for robust model evaluation.
    Built and optimized multiple classifiers: K-Nearest Neighbors (KNN) utilizing Cross-Validation (cross_val_score) to find the optimal K value; Decision Tree and SVM applying Grid Search (GridSearchCV) for exhaustive hyperparameter tuning.
    Evaluated model performance using Confusion Matrices, Precision, Recall, and Macro F1-scores.
  3.Unsupervised Learning: Clustering
    Explored natural data groupings without labeled ground truth using the first two principal components.
    Implemented K-Means and Hierarchical (Agglomerative) Clustering.
    Assessed cluster quality using Silhouette Score, Calinski-Harabasz Index, and Davies-Bouldin Index.
  4.Regression Analysis
    Predicted plant growth rates based on environmental factors (Sunlight, Water, Fertilizer Volume, Soil pH, Temperature).
    Developed Multiple Linear Regression models (with and without intercepts) using the Ordinary Least Squares (OLS) method via
statsmodels.
    Engineered non-linear relationships using Second-degree Polynomial Regression.
    Evaluated predictive accuracy using R-squared scores and RMSE.

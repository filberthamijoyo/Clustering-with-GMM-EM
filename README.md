# Cluster Analysis Using Gaussian Mixture Models

## Overview
Comprehensive analysis of Abalone dataset using both K-Means and Gaussian Mixture Models (GMM) with Expectation-Maximization (EM) algorithm. Includes comparative performance evaluation using silhouette scores.

## Key Features
1. **Advanced Data Preparation**  
   - One-hot encoding for categorical features
   - Min-max normalization of numerical features
   - Age transformation: Rings → Years (Rings + 1.5)

2. **Dual Clustering Approaches**  
   - **K-Means**:
     - Implementation with k=5 clusters
     - Silhouette score evaluation
   - **GMM/EM**:
     - Manual EM implementation (20 iterations)
     - sklearn comparison with covariance analysis

3. **Diagnostic Visualization**  
   - Feature distribution histograms
   - GMM density plots (manual vs sklearn implementations)
   - Cluster comparison metrics

4. **Model Evaluation**  
   - Silhouette coefficient comparison:
     - K-Means: 0.572
     - GMM (sklearn): 0.511

## Technical Implementation
```python
# Core analytical workflow
1. Data loading and preprocessing
2. K-Means clustering with silhouette analysis
3. Manual EM implementation for GMM
4. sklearn GMM comparison
5. Full-feature GMM clustering
6. Performance metric visualization

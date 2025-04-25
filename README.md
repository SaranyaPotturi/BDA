
This repository contains three machine learning projects implemented with Apache Spark. Each project demonstrates different capabilities of Spark's MLlib for big data analytics.

## Project 1: Classification Model with Spark

**Objective**: Predict categories or labels from a given dataset.

**Implementation**:
- Dataset: UCI Adult Income Dataset
- Algorithm: Random Forest Classifier
- Features: Categorical and numerical data processing, feature importance analysis

**Steps**:
1. Load and preprocess the Adult Income dataset
2. Convert categorical variables to numerical representations
3. Split data into training and testing sets
4. Train a Random Forest classifier
5. Evaluate model with Area Under ROC curve
6. Identify most important features for prediction

## Project 2: Clustering Model with Spark

**Objective**: Group data points into clusters based on similarity.

**Implementation**:
- Dataset: Online Retail Dataset
- Algorithm: K-means clustering
- Features: Customer segmentation using RFM (Recency, Frequency, Monetary) analysis

**Steps**:
1. Load the retail transaction data
2. Calculate RFM metrics for each customer
3. Scale features for better clustering results
4. Determine optimal number of clusters
5. Apply K-means algorithm
6. Evaluate with Silhouette score
7. Interpret customer segments for business insights

## Project 3: Recommendation Engine with Spark

**Objective**: Predict user ratings for items and generate recommendations.

**Implementation**:
- Dataset: MovieLens Dataset
- Algorithm: Alternating Least Squares (ALS)
- Features: User-based and item-based recommendations, similarity computations

**Steps**:
1. Load the MovieLens ratings data
2. Split into training and testing sets
3. Train ALS model with hyperparameter tuning
4. Generate rating predictions
5. Evaluate using Root Mean Square Error (RMSE)
6. Create movie recommendations for users
7. Find similar movies using latent factors

## Libraries

- PySpark (SQL and MLlib)
- Pandas
- NumPy
- Matplotlib
- Seaborn

This repository contains three machine learning projects implemented with Apache Spark.
## Project 1: Classification Model with Spark

**Objective**: Using Spark's classification algorithms, predict categories or labels from a given dataset.

**Implementation**:
- Dataset: UCI Adult Income Dataset
- Algorithm: Random Forest Classifier
- Features: Categorical and numerical data processing, feature importance analysis

**Steps**:
1. Load and preprocess the Adult Income dataset
2. Convert categorical variables to numerical representations
3. Split data into training and testing sets
4. Train a Random Forest classifier
5. Evaluate the model with the Area Under the ROC curve
6. Identify the most important features for prediction

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
4. Determine the optimal number of clusters
5. Apply the K-means algorithm
6. Evaluate with Silhouette score
7. Interpret customer segments for business insights

## Project 3: Book Recommendation Engine with Spark

**Objective**: Predict book user ratings and generate personalized reading recommendations.

**Implementation**:
- Dataset: Goodreads Books Dataset
- Algorithm: Alternating Least Squares (ALS)
- Features: User-based and item-based recommendations, book similarity computations

**Steps**:
1. Load the Goodreads books and ratings data
2. Split into training and testing sets
3. Train the ALS model with hyperparameter tuning
4. Generate rating predictions
5. Evaluate using Root Mean Square Error (RMSE)
6. Create personalized book recommendations for users
7. Find similar books using latent factors

## Libraries

- PySpark (SQL and MLlib)
- Pandas
- NumPy
- Matplotlib
- Seaborn

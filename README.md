# Categorizing Facebook Live Sellers in Thailand Using K-Means Clustering
This project applies the K-Means clustering algorithm to categorize Facebook Live sellers in Thailand based on their engagement metrics. The goal is to uncover intrinsic groups within the dataset that represent different types of sellers.

## Project Overview
K-Means is a popular clustering algorithm used to group data points into clusters based on their similarities. In this project, we use K-Means to identify distinct clusters among Facebook Live sellers in Thailand, using features such as the number of comments, shares, and reactions to their posts.

## Project Workflow
### 1. Introduction to K-Means Clustering
Overview of the K-Means algorithm, including its step-by-step process and methods for choosing the number of clusters (k).
### 2. Dataset Overview
The dataset used contains information about Facebook Live sellers in Thailand, with various metrics related to their engagement on the platform.
The dataset was sourced from the UCI Machine Learning Repository.
### 3. Data Exploration
Basic exploratory data analysis is performed to understand the dataset's structure, including checking for null values and irrelevant features.
### 4. Data Preprocessing
Preprocessing steps include feature scaling and encoding of categorical variables to prepare the data for clustering.
### 5. Model Implementation
The K-Means algorithm is applied to the preprocessed dataset.
The optimal number of clusters is determined using the elbow method or silhouette score.
### 6. Model Evaluation
The clusters formed are analyzed to understand the different groups of sellers and their characteristics.

## Results
The final clusters reveal distinct categories of Facebook Live sellers in Thailand, which can be used for further analysis or targeted marketing strategies.

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
## How to Run
1. Clone the repository.
2. Ensure you have the required dependencies installed.
3. Run the Jupyter Notebook to see the implementation and results.

## Author
Sahngyoon Rhee

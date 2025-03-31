Welcome to the Unsupervised Learning project! In this project, you'll apply a few different Unsupervised Learning techniques to gain insights from the a real-world dataset. 

## Context
Clustering is a core method in unsupervised learning that allows us to uncover hidden patterns and groupings in data *without* relying on labels. In this project, you will explore different clustering techniques and compare their effectiveness. 
Optionally, you'll use Principal Component Analysis (PCA) to reduce dimensionality and visualize the clusters you identify.

## Learning Objectives
By completing this project, you will have a chance to:
- Refine and apply your skills in cleaning and preparing datasets for unsupervised learning
- Practice applying clustering algorithms (K-Means, Hierarchical Clustering, DBSCAN)
- Practice evaluating clustering performance using metrics and visualizations
- (stretch) Learn some additional approaches for clustering visualization, including using PCA for dimensionality reduction, PCA biplots, and silhouette plots

## Business Case
Imagine you are a data scientist working for a company looking to segment its customer base. You have been given a dataset containing various customer metrics, such as business type, location, and spending history. Your task is to use clustering techniques to identify distinct customer groups and provide actionable insights based on these clusters.

# Part 1 - EDA
- Explore the dataset you've been given
    - Look for missing values, outliers, inconsistencies, etc
    - Examine the distribution of numerical and categorical features
    - Normalize/standardize the data if required for clustering algorithms  
Complete the `1 - EDA.ipynb` notebook and fill in **Step 1** in your `README.md` to demonstrate your completion of these tasks.

# Part 2 - K-Means Clustering
- Apply the K-Means algorithm to the dataset
- Use the elbow method to determine the optimal number of clusters
- Analyze the characteristics of the created clusters

Complete the `2 - K-Means Clustering.ipynb` notebook and fill in **Step 2** in your `README.md` to demonstrate your completion of these tasks

# Part 3 - Hierarchical Clustering
- Perform hierarchical clustering on the dataset
- Use a dendrogram to determine the optimal number of clusters
- Analyze the characteristics of the created clusters
Complete the `3 - Hierarchical Clustering.ipynb` notebook and fill in **Step 3** in your `README.md` to demonstrate your completion of these tasks

# Part 4 - DBSCAN
- Apply the DBSCAN algorithm to the dataset
- Experiment with different hyperparameters to optimize clustering results
- Identify (describe the features of) nay noise points (outliers) detected by the algorithm
Complete the `4 - DBSCAN.ipynb` notebook and fill in **Step 4** in your `README.md` to demonstrate your completion of these tasks

# Part 5 - Results and Evaluation
#### 5a - Evaluation
- Compare the results of K-Means, Hierarchical Clustering, and DBSCAN
    - Use metrics such as Silhouette Score, Rand Score, Mutual Information Score, etc
    - Compare the three clustering methods as evaluated by your chosen metrics
    - Evaluate how well each method aligns with the business case, and draw a conclusion about the most appropriate clustering technique for the dataset
    - Complete the `5 - Evaluation.ipynb` notebook to demonstrate your completion of these tasks
#### 5b - Results
- Answer the following prompts [in your `README.md`](README.md#results):
    1. Briefly discuss the strengths and weaknesses of each clustering method for this specific dataset
    2. Which clustering method performed best, and why?
    3. Were there significant differences in the clusters identified by your preferred algorithm? Describe them
    4. What actionable insights can be derived from the clustering results? 
    <br> 
    *eg:* 
        - "frequent repeat customers tend to purchase multiple types of products" 
        - "X large customer exhibits rare customer behavior and may require adjusted marketing strategy"
        - "customers in cluster Y frequently purchase many of the same products as each other - a recommender system could be effective for marketing to them"
#### 5c - Challenges
- Describe challenges you faced while completing the project [in your `README.md`](README.md#challenges) (troubleshooting, understanding of material before project, timeframe, etc)

#### 5d - Future Goals
- Describe potential future goals for this project [in your `README.md`](README.md#future-goals) (you should definitely return to this project after you graduate!)


# (stretch) Part 6 - PCA and Visualization

### 6a - PCA
- Apply PCA to reduce the dataset to two dimensions
- Visualize clusters as 2D scatter plots using PCA-transformed data

### 6b - PCA Biplots
- Create a PCA biplot to analyze the relationships between dataset features and clusters

### 6c - Silhouette Plots
- Create [Silhouette Plots](https://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_silhouette_analysis.html) to increase your understanding of your clusters' Silhouette Scores, and see if any of your opinions on the performance of the different clustering models change
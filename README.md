# Unsupervised-Learing-Clustering-Model
## 1. Bank Marketing Data Set 
**Goal:** The objective is to analyze the Bank Marketing dataset, which contains information about direct marketing campaigns of a Portuguese banking institution. The aim is to understand the data and use clustering techniques to segment the customers based on their attributes and campaign responses. 

**Approach:** 
  * Model: K-Means Clustering
  * Scaling: Applied scaling since dealing with distance metrics.
  * Steps: 
    * Exploratory Data Analysis (EDA): Understanding the dataset, analyzing the distribution of attributes.
    * Preprocessing: Handling missing values, encoding categorical variables, and scaling numerical features.
    * Modeling: Using K-Means algorithm to cluster the data based on customer attributes.
    * Tuning: Finding the optimal number of clusters using methods like the Elbow method and Silhouette score. 

**Insights:**

* Customer Age Distribution: Most customers are in the age range of 30 to 40.
* Loan Status: Distribution of customers having personal loans and housing loans.
* Marital Status: Most customers are married.
* Previous Campaigns: A significant number of clients were not contacted previously.
* Contact Duration and Type: Varied durations and contact types (cellular or telephone) affect the customer's response. 

## 2. Auto-mpg Dataset 

**Goal:** The objective of this project is to analyze the Auto-mpg dataset, which contains information on various attributes of cars. The goal is to use clustering techniques to group cars with similar characteristics. 

**Approach:** 
  * Model: Hierarchical Clustering
  * Steps: 
    * Data Comparison: Compare data points to find the most similar ones and merge them to create clusters.
    * Cluster Formation: Compare clusters to find similar clusters and merge them iteratively.
    * Dendrogram: Creating a dendrogram using the linkage() method to visualize the hierarchical clustering process.
    * Modeling: Implementing Hierarchical Agglomerative Clustering and interpreting the dendrogram to determine clusters. 

**Insights:** 
  * Clusters Identified: Several clusters were identified showing different groups of cars with similar characteristics.
  * Fuel Efficiency: Insights into which groups of cars are more fuel-efficient.
  * Comparison of Clusters: Visualization through dendrogram helped understand the relationships between different car groups.  

## 3. Mall Customer Segmentation Data 

**Goal:** The aim is to segment customers of a mall based on their spending habits and other attributes using clustering techniques. This helps in understanding different customer groups for targeted marketing. 

**Approach:** 
  * Model: Hierarchical Clustering (Agglomerative Clustering) 
  * Steps: 
    * EDA: Understanding customer demographics and spending behavior.
    * Selecting Features: Focusing on features like Annual Income and Spending Score.
    * Dendrogram Creation: Creating a dendrogram to determine the optimal number of clusters.
    * Modeling: Applying Agglomerative Clustering based on the dendrogram results.
    * Visualization: Plotting the clusters to interpret the segmentation. 

**Insights:** 

  * Customer Spending Patterns: Identification of different spending behaviors among customers.
  * Cluster Characteristics: Different clusters represent groups with varied spending on different product categories.
  * Targeted Marketing: Enabled targeted marketing strategies for different customer segments based on their spending habits. 


## 4. Moons Dataset 

**Goal:** The objective is to use the moons dataset, a synthetic dataset often used for demonstrating clustering and classification algorithms. The goal is to apply clustering techniques to correctly identify the two moon-shaped clusters. 

**Approach:** 
  * Model: DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
  * Steps: 
    * Model Initialization: Using DBSCAN with a reasonable epsilon value (eps=0.15).
    * Fitting Model: Fit the model to the data.
    * Anomaly Detection: Instances with a cluster index of -1 are considered anomalies.
    * Comparison: Create a model with K-Means to compare differences.
    * Visualization: Plotting the clusters and anomalies to visualize the results. 

**Insights:** 

  * Non-linear Clusters: DBSCAN effectively identified non-linear clusters that K-Means struggled with.
  * Anomalies: Identified outliers or noise points in the data.
  * Cluster Density: DBSCAN showed clusters based on density, which is effective for this type of dataset. 
 

## 5. Wholesale Customers Dataset 

**Goal:** The aim of this project is to segment customers of a wholesale distributor based on their annual spending on various product categories. This helps in identifying different customer types for targeted business strategies. 

**Approach:** 
  * Model: DBSCAN 
  * Steps: 
    * EDA: Understanding the spending patterns across various product categories.
    * Model Initialization: Using DBSCAN with a reasonable epsilon value (eps=2).
    * Fitting Model: Fit the model to the data to form clusters.
    * Anomaly Detection: Identify customers considered as anomalies by the algorithm.
    * Visualization: Plotting the clusters and anomalies to interpret the segmentation. 

**Insights:** 
  * Customer Segmentation: Identification of customer groups with similar spending patterns on fresh products, milk, grocery, frozen products, detergents, and delicatessen.
  * Anomalies: Detected outliers or unusual spending patterns.
  * Cluster Analysis: Helped understand different segments of wholesale customers, which can assist in optimizing marketing strategies and stock management. 

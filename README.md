# Outlier Detection

Outliers can distort analysis. 
Hence outlier detection is crucial steps in data analysis where we identify data points that significantly deviate from rest of data set.
Outliners can lead to incorrect conclusions and affect performance of machine learning models.

Some common outlier detection techniques:

**1. Statstical Methods**

    1. Z Score
    2. Modified Z Score
    3. IQR Inter Quartile Range
    4. Grubbs Test
    
**2. Machine Learning Based Methods**
   1. Isolation Forest
   2. Local Outlier Factor
   3. k-Nearest Neighbors k-NN
   4. One-Class Support Vector Machine
   5. Auto Encoders
      
**3. Distance Based Methods**
   1. Euclidean Distance
   2. Mahalanobis Distance
      
**4. Clustering Based Methods**
   1. DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
   2. K-Means Clustering
      
**5. Visual Methods**
   1. Box Plot
   2. Scatter Plot
   3. Histogram
      
**6. Robust Methods**
   1. Robust Regression
   2. Robust Principal Component Analysis (PCA)

**7. Ensable Methods**
   1. Random Cut Forest (RCF)

**8. Rule Based Methods**
   1. Domain-Specific Rules
  
**Considerations**
**Data Type**: The choice of outlier detection technique depends on whether the data is univariate or multivariate, continuous or categorical, and whether it follows a specific distribution.

**Scalability**: Some methods (e.g., distance-based) may not scale well to high-dimensional or large datasets. In such cases, tree-based or ensemble methods may perform better.

**Interpretability**: Methods like Z-Score and IQR are simple and easy to interpret, while machine learning-based methods (e.g., Isolation Forest, Autoencoders) may require more effort to understand.

Choosing the right outlier detection method depends on the dataset's characteristics, such as size, dimensionality, and distribution. 
In practice, a combination of techniques is often used to ensure robust detection of outliers.

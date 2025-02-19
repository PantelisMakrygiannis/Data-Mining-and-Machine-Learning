This repository contains a complete pipeline for **HARTH** using sensor data, covering **data preprocessing**, **exploratory data analysis (EDA)**, **machine learning classification** and **unsupervised clustering**.

##  Dataset

The dataset consists of CSV files representing data from sensors (back & thigh) collected during various human activities such as walking, running, cycling, etc. Each file contains time-series data with acceleration measurements and activity labels.

##  Features

- **Data Preprocessing:**  
  - Merging multiple CSV files into a single dataset.  
  - Dropping unnecessary columns and handling missing data.  

- **Exploratory Data Analysis (EDA):**  
  - Time-series visualization of sensor data for individual datasets.  
  - Correlation heatmaps for understanding sensor interdependencies.  
  - Distribution plots and histograms for activity frequency analysis.  

- **Machine Learning (Supervised):**  
  - Implemented classifiers:  
    - **Multi-Layer Perceptron (MLP)**  
    - **Random Forest**  
    - **Gaussian Naive Bayes**  
  - Evaluation Metrics: Precision, Recall, F1-Score, Training & Testing Accuracy.  
  - Visual comparison of classifier performances using bar plots.  

- **Unsupervised Learning (Clustering):**  
  - Applied **K-Means** and **Agglomerative** clustering on normalized data.  
  - Determined the optimal number of clusters using **Silhouette Score**.  
  - Visualized clusters using **PCA** for dimensionality reduction.  

##  Visualizations

-  Time-series plots for sensor data (Back & Thigh).
-  Correlation heatmaps between different sensor axes.
-  Boxplots for acceleration values across all datasets.
-  Histograms for activity frequency distribution.
-  Silhouette Score plots to determine optimal K in K-Means.
-  PCA scatter plots for cluster visualization.

##  Libraries Used

- pandas  
- numpy  
- matplotlib  
- seaborn 
- scikit-learn    

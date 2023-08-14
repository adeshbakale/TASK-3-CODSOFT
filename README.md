# TASK-3-CODSOFT

#Aim -
Create a model to classify iris flowers into different species using their measurements.

#Libraries -
Used libraries: numpy, pandas, sklearn.cluster.KMeans, matplotlib.pyplot, seaborn.

#Dataset -
Used seaborn's load_dataset to get iris flower data with measurements and species.

Data Exploration
Loaded data and displayed the first 5 rows.
Encoded 'species' to numbers.
Displayed statistics and checked missing values.
Data Visualization
Made 3D scatter plots for species, petal length/width, sepal length/width.
Created 2D scatter plots for species and sepal length/width.
K-Means Clustering
Used Elbow Technique to find the best K value (number of clusters).
Applied KMeans algorithm with K=3.
Predicted cluster labels for data points.
Accuracy Check
Calculated confusion matrix to check KMeans clustering accuracy.
Visualized confusion matrix to compare true and predicted labels.
In simple terms, the project aims to classify iris flowers based on measurements. Steps include data loading, exploration, visualization, K-Means clustering, and accuracy assessment.

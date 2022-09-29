# Myopia Clusters

In this project, I applied what I learned about unsupervised learning by fitting data to a model and using clustering algorithms to place data into groups. 


## Project Contents

This project is broken down into three parts: 

* Part 1: Prepare the Data

* Part 2: Apply Dimensionality Reduction 

* Part 3: Perform a Cluster Analysis with K-means


### Part 1: Prepare the Data

1. I read `myopia.csv` into a Pandas DataFrame.

2. I removed the "MYOPIC" column from the dataset.

3. I standardize my dataset so that columns that contain larger values do not influence the outcome more than columns with smaller values.

### Part 2: Apply Dimensionality Reduction

1. I performed dimensionality reduction with PCA. 


2. I further reduced the dataset dimensions with t-SNE and visually inspect the results. To do this, I run t-SNE on the principal components, which is the output of the PCA transformation. 

3. I created a scatter plot of the t-SNE output.

### Part 3: Perform a Cluster Analysis with K-means

I create an elbow plot to identify the best number of clusters and copleted the following steps:

* I used a `for` loop to determine the inertia for each `k` between 1 through 10. 

* I determined where the elbow of the plot is, and at which value of `k` it appears.




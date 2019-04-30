# Data Science Quiz

### Instructions

- Fork and Clone
- Work on quiz
- Push back up to your repository

### Questions

1. A vector is given, `[2,3,9]`. What's the norm?

9.7 --- np.linalg.norm

2. I have a biased coin. P(T) = 0.45. What's the probability, if I flip the coin 100 times, that I will get exactly 14 heads?

binom(100, 0.55).pmf(14)

3. What is the rank of a matrix?

Checking to see if the rows/cols are linearly independent?

4. Why is rank important for Linear Regression?

Checking for co-linearity.

5. What is the purpose of the sigmoid function in a Logistic Regression model?

Gives your probability value. Log odds is the input.

6. What is bias vs variance?

Bias is prediction differs from true value, Variance is the spead of the data from the mean.

7. What is a hyperparameter? What part of the dataset (train, validation or test) is responsible for determining this value?

It is parameter to your model, before you fit the data. Train data set.

8. Model selection via cross validation. What part of the dataset (train, validation or test) is responsible for choosing the best model?

Validation data set.

9. What is parametric vs non-parametric model?

Parametric has fixed number of parameters.

10. What models do you need to scale the data prior to fitting?

When using distance metric ... km to um ... sensitive to scale. (lin reg, log, nn)

Invariant to scale are Trees.

MinMaxScaling = 0 to 1
StandardScaling = mean of 0, stdev 1

11. What is entropy? Which model uses this concept?

Measure of disorder. Trees.

12. How is a random forest generated?

Sampling with replacement - bagging
Split on not all featurs = sqrt of n

13. How do you determine the correct number of clusters when using KMeans?

Elbow method.

14. What is a dendrogram / what is it used for?

A dendrogram is a type of tree diagram showing hierarchical clustering — relationships between similar sets of data.

Used to pick the number of clusters.

15. What is linkage and what are the types?

Linkage is the distance between clusters. Simple, Complete, Average, and Centroid Methods are the main versions.

16. How does a recommender model work?

Matrix factorization (non-negative). User and (Item or Movie). Latent hidden features.

UxI = M

17. How can you reduce the number of features in a model?

L1 (lasso), PCA, Tree (feature importance)

18. What is a good use of PCA?

Visualization, feature reduction

19. In general, how do neural networks "learn"?

Back propagation.

20. What is your favorite model? Why?

Whichever gives best score - Rajani



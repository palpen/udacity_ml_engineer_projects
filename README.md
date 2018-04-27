# Udacity Machine Learning Engineer Nanodegree Projects

1. [Naive Bayes Algorithm for Spam Detection (tutorial)][1]
    * Explored the bag-of-words model, the naive Bayes classifier, and some model evaluation on a natural language processing application for email spam detection
2. [Introduction to Decision Trees using the Titanic Survival Data][2]
    * Basic implementation of decision trees to predict who survived when the Titanic sank
3. [Model Evaluation and Validation using Boston Housing Prices Data][3]
    * Used decision tree regression to predict house prices in Boston using various home and neighborhood characteristic data
    * Used grid search to tune model
    * Analyzed model performance using learning and complexity curves. Discussed implications of changing model hyperparameters on the bias-variance trade-off
4. [Supervised Learning to Find Charity Donors][4]
    * Used AdaBoost with the decision trees as the base estimator to predict income levels using various demographic data as features. The goal is to predict which individuals earned more than \$50,000 and are more likely to make a charitable donation
    * Tested logistic regression and SVM models to compare performance
    * Tuned model hyperparameters using grid search with 3-fold cross validation
    * Accounted for unbalanced classification in performance metric (with emphasis on precision)

5. [Unsupervised Learning for Customer Segmentation][5]
    * Used principal component analysis to reduce the dimension of the data to two dimensions while retaining about 73% of the explained variation (two dimensions was chosen for easier visualization)
    * Used the Gaussian mixture model (GMM) clustering algorithm to identify market segments using the two-dimensional dataset reduced using PCA. GMM allows for soft-clustering and more flexible cluster shape compared with K-means
    * Computed the Silhouette coefficient to determine optimal number of clusters
    * General data preprocessing (to deal with skewed features and outliers) and visualization

[1]: https://github.com/palpen/udacity_ml_engineer_projects/blob/master/naive_bayes_spam.ipynb
[2]: https://github.com/palpen/udacity_ml_engineer_projects/blob/master/titanic_survival_exploration/titanic_survival_exploration.ipynb
[3]: https://github.com/palpen/udacity_ml_engineer_projects/blob/master/boston_housing/boston_housing.ipynb
[4]: https://github.com/palpen/udacity_ml_engineer_projects/blob/master/finding_donors/finding_donors.ipynb
[5]: https://github.com/palpen/udacity_ml_engineer_projects/blob/master/customer_segments/customer_segments.ipynb

Abstract: This paper investigates the optimal age for harvesting crabs in commercial crab farming, addressing the need for efficient management to maximize profitability. Utilizing data analytics techniques, including statistical modeling and machine learning algorithms, the study analyzes crab growth patterns to determine the ideal timing for harvesting based on a variety of features, such as height, weight, and shell metrics. By offering insights into the relationship between crab age and input features, the project aims to accurately model crab age, which could be useful for the crab farming industry.

EXECUTIVE SUMMARY

Study goal: We aim to build accurate models to predict crab age and classify crabs as old or young based on the indicator features. We also want to identify which features are the most important in determining age.

Data description: We utilize a Kaggle dataset of 3891 observations and 9 features, including physical features such as height, weight, shell weight, diameter, age, and more. The data includes information about crabs from the Boston Area from 2018-2019.

Methods Used: Our methods include EDA, PCA for clustering, linear regression, regularization (LASSO, Ridge, and Elastic Net), logistic regression, Random Forests, XGBoost, Feedforward Neural networks, and PCA on latent vectors, along with various data visualizations.

Findings: The study found that PCA clustering effectively distinguishes crab age in three dimensions, with vanilla regression outperforming regularized models (MSE 5.24 vs. 5.39). Logistic regression achieved 78% accuracy but with a low recall rate (55%). Random Forest models surpassed XGBoost, identifying key predictors (shell weight, shucked weight). The feedforward neural network achieved 80% classification accuracy, successfully predicting age and classifying crabs, with PCA visualizations revealing distinct age clusters.

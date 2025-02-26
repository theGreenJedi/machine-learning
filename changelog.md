# Changelog

The changelog will record what content was **changed** (e.g. changed an existing paragraph to a better-explained version, re-ran the notebook using an updated version of the package), **added** (e.g. a completely new jupyter notebook) **fixed** (e.g. grammar mistakes, typos, redundant spaces)

## [2017-07]

### Changed

- Gradient Boosting Machine (GBM) from scratch. [[nbviewer]](http://nbviewer.jupyter.org/github/ethen8181/machine-learning/blob/master/trees/gbm/gbm.ipynb)
	- Add a made up number example on how GBM works
- data_science_is_software. [[nbviewer](http://nbviewer.jupyter.org/github/ethen8181/machine-learning/blob/master/data_science_is_software/notebooks/data_science_is_software.ipynb)]
	- Mention `nbdime`, a tool that makes checking changes in jupyter notebook on github a lot easier
	- Mention semantic versioning (what each number in the package version usually represents)
	- Mention `configparser`, a handy library for storing and loading configuration files
- K-fold cross validation, grid/random search from scratch. [[nbviewer](http://nbviewer.jupyter.org/github/ethen8181/machine-learning/blob/master/model_selection/model_selection.ipynb)]
	- Minor change in Kfolds educational implementation (original was passing redundant arguments to a method)
	- Minor change in random search educational implementation (did not realize scipy's .rvs method for generating random numbers returns a single element array instead of a number when you pass in size = 1)

## [2017-06]

This is the first time that the changelog file is added, thus every existing notebook will fall under the added category. Will try to group the log by month (one or two) in the future. Note that this repo will be geared towards Python3. Hence, even though the repo contains some R-related contents, they are not that well maintained and will most likely be translated to Python3. As always, any feedbacks are welcomed.

### Added

- Others (Genetic Algorithm)
- Regression (Linear, Ridge/Lasso)
- Market Basket Analysis (Apriori)
- Clustering (K-means++, Gaussian Mixture Model)
- Deep Learning (Feedforward, Convolutional Neural Nets)
- Model Selection (Cross Validation, Grid/Random Search)
- Dimensionality Reduction (Principal Component Analysis)
- Classification (Logistic, Bernoulli and Multinomial Naive Bayes)
- Text Analysis (TF-IDF, Chi-square feature selection, Latent Dirichlet Allocation)
- Tree Models (Decision Tree, Random Forest, Extra Trees, Gradient Boosting Machine)
- Recommendation System (Alternating Least Squares with Weighted Regularization, Bayesian Personalized Ranking)
- Python Programming (e.g. logging, unittest, decorators, pandas category type)

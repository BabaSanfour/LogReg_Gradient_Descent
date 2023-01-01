
This is an implemtation from scratch (using only numpy) for Binary and Multiclass Logitic Regression, Gradient Descent with it's variations (SGD, ADAPRop, ADAM). 

The jupyter start with some data analysis on the publicly available datasets: IMDB movie reviews and Twenty groups data and selecting features using Bag of Words and Z-score.

In the experiments we test the impact of using different Optimzers, Hyper paramaters, effect of data normalization... With a comparison to kNN results (from sklearn)

The IMDB Reviews data can be downloaded from here: http://ai.stanford.edu/~amaas/data/sentiment/.

The 20-news group dataset can be loaded directly using sklearn.datasets.fetch_20newsgroups 
(https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_20newsgroups.html).

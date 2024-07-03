# TODO
- DONE try to use as much as possibile the pyod package instead of sklearn. 
- DONE use ROC-AUC as metric 
- use PR-AUC as the metric for grid search
- implement more of supervised learning methods, such as MLP, XGBOOST and SVM.
- implement AE, LOF.
- visualize the dataset, like pca. take distribution .value_counts(). do the correlation matrix and plot as heat map.
- validate the supervised models, to understand overfitting (compare with the fact that you have done Cross validation in grid search)


# techniques
1. The first idea should be to use the LB-ABOD algorithm proposed in the paper Angle-Based Outlier Detection in High-dimensional Data [link](https://www.dbs.ifi.lmu.de/~zimek/publications/KDD2008/KDD08-ABOD.pdf). I like it because it use also kNN to achieve the outliers.
2. extended isolation forest o isolation forest 
3. PCA
4. kNN
5. deep iForest

# project relation
- start with preprocessing and visualization of the data
- reasons why randomforest works better
- 
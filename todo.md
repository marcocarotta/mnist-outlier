# TODO
- DONE try to use as much as possibile the pyod package instead of sklearn. 
- DONE use ROC-AUC as metric 
- DONE use PR-AUC as the metric for grid search
- DONE implement more of supervised learning methods, such as MLP, XGBOOST and SVM.
- REMOVED implement AE, LOF.
- DONE visualize the dataset, like pca. take distribution .value_counts(). do the correlation matrix and plot as heat map.
- validate the supervised models, to understand overfitting (compare with the fact that you have done Cross validation in grid search)
- DONE add complexity of the algorithms
- DONE introduce the metrics that you've used to validate you model and explain why you have used it
- DONE spiegare che ti aspetti che il supervised funziona meglio visto che dalla visualizzazione con la pca non sembrano ben separate le classi (domandarsi se questa cosa ha senso)
- DONE explains how you have planned to tackle the problem
- DONE spiegare bene i risultati e perche li reputi buoni
- DONE sitography and bibliography
- DONE spostare la sperimentazione tSNE e kmeans nella parte sul dataset bilanciatao e vedere che succede
- DONE add comments between blocks of code. before PCA 3D; after PCA 2D; tSNE is unsupervised.; remove UMAP; comment correlation matrix, write it is for the features; explain better what do you represent in plots in the tSNE+KMeans part;



# techniques
1. The first idea should be to use the LB-ABOD algorithm proposed in the paper Angle-Based Outlier Detection in High-dimensional Data [link](https://www.dbs.ifi.lmu.de/~zimek/publications/KDD2008/KDD08-ABOD.pdf). I like it because it use also kNN to achieve the outliers.
2. extended isolation forest o isolation forest 
3. PCA
4. kNN
5. deep iForest

# project relation
- start with preprocessing and visualization of the data
- reasons why randomforest works better than isolation forest

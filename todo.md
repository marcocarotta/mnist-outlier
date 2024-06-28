# miscellanea
- use more than one algorithm to detect outliers
- try to use as much as possibile the pyod package instead of sklearn. 
- use ROC-AUC as metric 

# techniques
1. The first idea should be to use the LB-ABOD algorithm proposed in the paper Angle-Based Outlier Detection in High-dimensional Data [link](https://www.dbs.ifi.lmu.de/~zimek/publications/KDD2008/KDD08-ABOD.pdf). I like it because it use also kNN to achieve the outliers.
2. extended isolation forest o isolation forest 
3. PCA
4. kNN
5. deep iForest
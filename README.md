# clustering
Unlike supervised methods, clustering is an unsupervised method that works on datasets in which there is no outcome (target) variable nor is anything known about the relationship between the observations, that is, unlabeled data.<br>
Example - In shopping complex two T-shirts are placed near to each other even if they are not exactly same. This because if customer choose to buy a T-shirt he would go to the T-shirt section and not to dairy section. Therefore placing the other T-shirt in T-shirt section makes more sense.


## Various approach of Clustering algorithims -
- Divisive approach - Divide the dataset and try to find the suitable number of 'K' .<br>
Example - K mean plus plus analysis
- Agglomeration approach - deploys Dendrogram for finding the suitable number of 'K' .<br>
Example - Hierarchical cluster analysis.

## Types of Clustering algorithums 
- K mean analysis - This approach has further 3 types of analysis -
  - K mean. 
  - K mean plus plus.
  - Mini batch K mean.
- Hierarchical cluster analysis.
- D.B.S.C.A.N. (Density Based Spatial Clustering of Applications with Noise).

## DBSCAN cluster analysis :
### Need of DBSCAN:
- K-Means and Hierarchical Clustering fails in creating clusters of arbitrary shapes. They are not able to form clusters based on varying densities. That’s why we need DBSCAN clustering.
- It detects the noise far more precisely then K-Means and Hierarchical Clustering.  

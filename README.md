# Project--ML-15


<table>

**In this project we will build the Model Hierarchical Clustering for clustering Spending Score and make different clusters based on different features in the dataset**.<br></br>  

Hierarchical clustering is a popular method for grouping objects. It creates groups so that objects within a group are similar to each other and different from objects in other groups. Clusters are visually represented in a hierarchical tree called a dendrogram.<br></br>
Hierarchical clustering has a couple of key benefits:<br>

There is no need to pre-specify the number of clusters. Instead, the dendrogram can be cut at the appropriate level to obtain the desired number of clusters.
Data is easily summarized/organized into a hierarchy using dendrograms. Dendrograms make it easy to examine and interpret clusters.<br></br>

**Hierarchical clustering algorithms are of 2 types**:<br></br>
**1. Divisive**-<br></br>
This is a top-down approach, where it initially considers the entire data as one group, and then iteratively splits the data into subgroups. If the number of a hierarchical clustering algorithm is known, then the process of division stops once the number of clusters is achieved. Else, the process stops when the data can be no more split, which means the subgroup obtained from the current iteration is the same as the one obtained from the previous iteration (one can also consider that the division stops when each data point is a cluster).<br></br>
**2. Agglomerative**-<br></br>
It is a bottom-up approach that relies on the merging of clusters. Initially, the data is split into m singleton clusters (where the value of m is the number of samples/data points). Two clusters are merged into one iteratively thus reducing the number of clusters in every iteration. This process of merging clusters stops when all clusters have been merged into one or the number of desired clusters is achieved.<br></br>

**Steps to do Hierarchical Clustering**<br></br>
Step 1: Compute the proximity matrix using a particular distance metric.<br></br>
Step 2: Each data point is assigned to a cluster.<br></br>
Step 3: Merge the clusters based on a metric for the similarity between clusters.<br></br>
Step 4: Update the distance matrix.<br></br>
Step 5: Repeat Step 3 and Step 4 until only a single cluster remains.



**Important- Note: Explore the dataset once before going through the code.**

</table>


**So what are you waiting for...? Jump to the code to get started. As usual for any doubt or query see you in pull request section 😁😂. Thanks!**

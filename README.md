# CryptoClustering
Module 19 Challenge for UPenn Data Science Bootcamp

## Objective
For this challenge, we used the K-means algorithm and principal component analysis (PCA) to determine if various cryptocurrency prices were affected by 24-hour or 7-day price changes.

## Findings
After the scaling the data, the optimal number of clusters using K-means is 4.  After running the principal component analysis, we found that 3 principal components accounted for approximately 89.5% of the variance in the data.  When K-means was run again using the PCA findings, the optimal number of clusters was still found to be 4.  However, PCA resulted in tighter clustering of the data.

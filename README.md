# 19-Crypto-Clustering

completed by Li Chen 5/9/2024

# Description
To predict if cryptocurrencies are affected by 24-hour or 7-day price changes, this challenge:
    compares data from different crypto currencies
    propose clustering by 
        normalized original data or 
        PCA (Principal Compoents Analysis)
    use the elbow method to determine the optimal number of clusters
        it turns out k = 4 is the best value in both methods

* follow the CRY rule, define functions for elbow dataframe and model fit process

# Conclusion
Reducing feature number from originally 7 to 3 principle components, makes the clustering more straightforward, easier to identify clusters visually.
Loss of variability is very little.



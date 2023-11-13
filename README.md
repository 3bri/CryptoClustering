# CryptoClustering

Brian Guenther

In this project we undertook identifying clusters of cryptocurrencies using both normalized data and Principle Component Analysis (PCA).  Both approaches identified four clusters of cryptocurrencies.  Two larger clusters and two singlet clusters consisting of ethlend and Celsius-degree-token, respectively.  Therefore, both approaches provided similar information.  Arguably, the separation of the singlet clusters was more clearly identified in the PCA approach, which should also provide more efficient computation with much larger datasets.

The process of this analysis involved k-means clustering algorithm with several ranges of cryptocurrency values over different time frames, which were then normalized.  Determining the best value for K was done graphically by testing values of k between 1 and 10 versus the number of clusters and plotting this.  After obtaining a clustering result, this process was repeated but with PCA to reduce the number of columns of data under consideration.  While PCA reduced the number of columns from seven to three, calculation of the explained variance indicated that approximately 90% of the information for clustering was preserved.  PCA also identified two larger clusters and two singlet clusters.

In addition to providing this analysis, the code contains some additions to limit the number of “future warnings” that were produced to aid in the readability of this code.   I was aided in dealing with the warnings by discussion with my tutor Kourt Bailey.  He also provided guidance on the production of the composite plots.  Otherwise, this work was based on experience from class activities and experimentation while writing the code.

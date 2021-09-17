# Recommendation-System

Recommendation Systems are a type of system designed to recommend different products or services to the user that system predict as most likely to purchase by the user. In nutshell recommendation systems try to find out the match between items and users.

Examples for the companies use these systems are Netflix, Youtube and Amzom etc.

## 1.Popularity  Based Recommendation System

This type of recommendation systems simply recommend the products or services which are most popoular among the users.

For example, if there is a trending movie among users, system will recommend that movie to other users. This recommendation system is useful when there are new users who just signed it. As new users do not have historical data it is difficult to use other recommendation systems where recommending most trending products/services is possible. 

The demerits of this recommendation system is it is not personalized.
 
Example
 - Google News: News filtered by trending and most popular news.
 - YouTube: Trending videos.

## 2.Contenet Based Recommendation system

This is a type of recommendation system which recommend based on the features of products/services user has already purchased. In nutshell, this recommendation system recommend similar products user has purchased. 

The system is using various attributes to compute the similarity between products/services. In practice, for computing similarity between numberic attributes *Euclidean distance* is used, for texual attributes *Cosine similarity* is used and for categorical attributes *Jaccard similarity* is used.

The adavantages of this system is as this system recommend based on content of products/services user has already purhcased, no requirement for much of user's data. But again, there should be good volume of product data with attributes to compute similarity.

![image](https://user-images.githubusercontent.com/34208844/133703335-ad2bea13-3341-42e4-9150-e17046a06c26.png)


## .Collaborative filtering

![image](https://user-images.githubusercontent.com/34208844/129284010-737761fa-fb1a-4c26-8243-fa0b344c63ca.png)

  a) User-based nearest-neighbor collaborative filtering
  b) Item-based nearest-neighbor collaborative filtering
  c) Singular value decomposition and matrix-factorization
        SVD is a matrix factorization method that is used to reduce the features in the data by reducing the dimensions from N to K where (K<N). 

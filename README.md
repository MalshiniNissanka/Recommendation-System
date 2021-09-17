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

<p align="center">
<img  src="https://user-images.githubusercontent.com/34208844/133703335-ad2bea13-3341-42e4-9150-e17046a06c26.png" width="300" height="300" />
 </p>

## 3.Collaborative filtering

This is a method where the recommendation system make use of user preference on products/services for recommendation. As this method use users' historical data, it makes the assumption user's preference will be the same in future as well. 

There are main two method of finding user preference on products/services *Explicit Rating*(user's direct feedbacks such as ratings on products and so on) and *Implicit Rating*(Indirect preferences such as page clicks, purchased records and so on). 

 <p align="center">
<img  src="https://user-images.githubusercontent.com/34208844/129284010-737761fa-fb1a-4c26-8243-fa0b344c63ca.png" width="600" height="400" />
 </p>
 
Followings are different types of collaborative filtering

  - a) User-based nearest-neighbor collaborative filtering
  - b) Item-based nearest-neighbor collaborative filtering
  - c) Singular value decomposition and matrix-factorization (SVD is a matrix factorization method that is used to reduce the features in the data by reducing the dimensions from N to K where (K<N).)
 
### a) User-based nearest-neighbor collaborative filtering

This is a colloaborative filtering technique which is *memory-based*. The method assumes users with similar characteristics have similar taste. 

<p align="center">
<img  src="https://user-images.githubusercontent.com/34208844/133711916-644746c0-2270-4697-9cac-fe6738ec2680.png" width="500" height="400" />
 </p>
 
 In the above figure if we take user B and E both have given the similar ratings for book and remote controller and user C and E given the similar ratings for wall picture and book which leads to the conclution B,C,E users have similar preferences. Also, we can see B and C disliked for television, hence system will not recommended television to the user E.

### b) Item-based nearest-neighbor collaborative filtering

In this method instead of focusing on other users with similar preferences, we focus only about the user's preference on different products/services. Then the system try to find similar products/services user will prefer from all products/services available. 

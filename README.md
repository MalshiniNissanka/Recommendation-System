# Recommendation-System

Recommendation Systems are a type of system designed to recommend different products or services to the user that system predict as most likely to purchase by the user. In nutshell recommendation systems try to find out the match between items and users.

Examples for the companies use these systems are Netflix, Youtube and Amzom etc.

1.Popularity  Based Recommendation System

It is a type of recommendation system which works on the principle of popularity and or anything which is in trend. These systems check about the product or movie which are in trend or are most popular among the users and directly recommend those.

For example, if a product is often purchased by most people then the system will get to know that that product is most popular so for every new user who just signed it, the system will recommend that product to that user also and chances becomes high that the new user will also purchase that. 

Merits of popularity based recommendation system
 It does not suffer from cold start problems which means on day 1 of the business also it can recommend products on various different filters.
 There is no need for the user's historical data.
 
Demerits of popularity based recommendation system
 Not personalized 
 The system would recommend the same sort of products/movies which are solely based upon popularity to every other user.
 
Example
 Google News: News filtered by trending and most popular news.
 YouTube: Trending videos.

2.Classification model

The model that uses features of both products as well as users to predict whether a user will like a product or not.

Limitations of Classification Model
 It is a rigorous task to collect a high volume of information about different users and also products.
 Also, if the collection is done then also it can be difficult to classify. 
 Flexibility issue.

3.Contenet Based Recommendation system

It is another type of recommendation system which works on the principle of similar content. If a user is watching a movie, then the system will check about other movies of similar content or the same genre of the movie the user is watching. There are various fundamentals attributes that are used to compute the similarity while checking about similar content. 

For computing the similarity between numeric data, Euclidean distance is used, for textual data, cosine similarity is calculated and for categorical data, Jaccard similarity is computed.

Merits
  There is no requirement for much of the user’s data.
  We just need item data that enable us to start giving recommendations to users.
  A content-based recommender engine does not depend on the user’s data, so even if a new user comes in, we can recommend the user as long as we have the user data to build his profile.
  It does not suffer from a cold start.

Demerits
  Items data should be in good volume.
  Features should be available to compute the similarity.

4.Collaborative filtering

![image](https://user-images.githubusercontent.com/34208844/129284010-737761fa-fb1a-4c26-8243-fa0b344c63ca.png)

  a) User-based nearest-neighbor collaborative filtering
  b) Item-based nearest-neighbor collaborative filtering
  c) Singular value decomposition and matrix-factorization
        SVD is a matrix factorization method that is used to reduce the features in the data by reducing the dimensions from N to K where (K<N). 

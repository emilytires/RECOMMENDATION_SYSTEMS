# RECOMMENDATION_SYSTEMS

 A recommender system is an application of machine learning that predicts the future preference of a set of products for a user and provides personalized suggestions. This script is a practical introduction to the main Recommender System (RecSys) techniques.

The main families of methods for recommendation system are Collaborative Filtering, Content Based Filtering and Hybrid System. 

1. Content Based Filtering

  Content-based filtering, also referred to as cognitive filtering, recommends items based on a comparison between the content of the items and a user profile.The main idea here is to suggest items based on a particular item. In particular, various candidate items are compared with items previously rated by the user and the best-matching items are recommended.
  
 2. Collaborative Filtering
 
  To address some of the limitations of content-based filtering, collaborative filtering uses similarities between users and items simultaneously to provide recommendations. The collaborative filtering recommendation technique depends on finding similar users to a target user to make personalized recommendations. Collaborative filtering recommender systems do not require item metadata like content-based recommendation systems. It relies solely on past user-item interactions to render new recommendations.
  
   2.1 User Based Content Filtering 

   This method aims at finding similar users and recommendations are made to a user based on what a similar user has liked. The similarity between users is calculated using either Cosine Similarity or Pearson Correlation.
      
   2.2 Item Based Content Filtering

  Here, new items are recommended to users based on their similarity with the items that the user has rated- highly in the past.
 
 3. Hybrid System

  This method uses combining collaborative filtering and content-based filtering could be more effective than content based filtering and collaborative filtering approaches in some cases. 

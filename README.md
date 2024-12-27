
Movie Recommendation System

Recommender System is a system that seeks to predict or filter preferences according to the user choices Recommender systems are utilized in a variety of areas including movies, music, news, books, research articles, search queries, social tags, and products in general.

Recommender systems produce a list of recommendations in any of the two ways 
1. Collaborative filtering: Collaborative filtering approaches build a model from the users past behavior as well as similar decisions made by other users This model is then used to predict items that users may have an interest in.
2. Content-based filtering: Content-based filtering approaches uses a series of discrete characteristics of an item in order to recommend additional items with similar properties Content-based filtering methods are totally based on a description of the item and a profile of the users preferences It recommends items based on the users past preferences.
Lets develop a basic recommendation system using Python and Pandas. 
Lets focus on providing a basic recommendation system by suggesting items that are most similar to a particular item, in this case, movies. It just tells what movies/items are most similar to the users movie choice.

Data Collection :
The dataset has been obtained from Grouplens.
This dataset (ml-20m) describes 5-star rating and free-text tagging activity from MovieLens, a movie recommendation service. It contains 20000263 ratings and 465564 tag applications across 27278 movies. These data were created by 138493 users between January 09, 1995 and March 31, 2015. This dataset was generated on October 17, 2016.
Users were selected at random for inclusion. All selected users had rated at least 20 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.
The data are contained in the files genome-scores.csv, genome-tags.csv, links.csv, movies.csv, ratings.csv and tags.csv.
For our objective, we would be using "ratings.csv" and "movies.csv" data files.

Modelling :
The following modelling approach was used in the project:
Loading & exploring the Movie and User ratings data
Creating User-Item Matrix, User-User and Item-Item similarity matrices for Movie Recommendations
Creating feature and applying ML models to predict the ratings for unseen movies for a user
The detailed analysis and model creation can be found in the .ipynb file.

Conclusions :
In this project, we learned the importance of Recommendation Systems, the types of recommender systems being implemented, and how to use matrix factorization to enhance a system.
We then built a movie recommendation system that considers user-user similarity, movie-movie similarity, global averages and matrix factorization. These concepts can be applied to any other user-item interactions systems.
We tried generating recommendations based on similarity matrix and Collaborative Filtering techniques.
We tried to predict the ratings for movies that the user might give based on its past rating behaviours and measure the accuracy using RMSE and MAPE error metrics.

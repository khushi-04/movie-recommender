# movie-recommender

This project is my first attempt at building a recommender system. I use python and Jupyter Notebook to build this project. It will use collaborative filtering as the method for this system. It also includes all the data cleaning and exploratory data analysis for the movie lens data set. 

As it is explained in the code itself, this is how the system works:
1. I train the KNN model using the Euclidean distance and brute force algorithm using the user_to_movie_df.
2. For the recommender function itself, we initialize it to take three parameters. 
    * These three parameters are user id (the user), the number of users (how many users to compare to), and the number of recommendations (number of movies to finally output as recommendations). 
    * Using the KNN model, we find the most similar users and aggregates their ratings. It then gets the average of those ratings from those similar users and returns the top n number of recommendations.

Although this explanation is a little confusing, the code will make sense. Scroll to the end of the code to the recommender system to take a look at how this was implemented and put together. 

Enjoy!
# MovieLens-Capstone-Project-for HarvardX-PH125.9x-
MovieLens Introduction
The MovieLens data set was collected by GroupLens Research. Can we predict movie ratings based on user preferance, age of a movie? Using the MovieLens data set and penalized least squares, the following R script calculates the RMSE based on user ratings, movieId and the age of the movie.
The MovieLens data set contains 10000054 rows, 10677 movies, 797 genres and 69878 users.
The steps performed for analysis of the data - Created an age of movie column - Graphic displays of movie, users and ratings in order to find a pattern or insight to the
behavior of the data. - Explored Genres to determine if ratings could be predicted by genre. - Explored the Coefficient of Determination R-Squared - Graphically explored the linear correlation coefficient, r-value - Calculate RMSE based on movieId, userId, and age of the movie.
After exploring the movies through graphical representations and calculating RMSE, I found the best predictor for ratings was movieId, userId. The age of the movie didn’t change the rmse.
The final RMSE is 0.8252
The following are the libraries I used to explore the data. Explorations that didn’t seem to lead to an insight were taken out of the script.



 
  



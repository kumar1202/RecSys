# RecSys
A hybrid movie recommender system which uses Pearson Correlation Similarity Measure for comparing users and K-Means clustering for classifying movies.

A utility matrix is pickled in this repo which stores the rating for each user-item pair.
The backend handles the recommendation part:-
  1. Pearson Correlation Similarity - Calculates the measure of similarity between two users on the basis of the utitlity                      
                                      loaded from the pickled file.
  2. K-Means Clustering - Classifies the movies into clusters of different genres.

An user interface is made using Tkinter Module in Python 3, which prompts for the input of ratings for 18 movies, then displays the recommended movies on the basis of the ratings submitted.



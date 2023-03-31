# CA05-6070
Instruction for the assignment are provided below:

We are to build a  kNN based Movie Recommender Engine to find:
Given a movies data set, what are the 5 most similar movies to a movie query?

Data Source and Contents Used:
File Location: https://github.com/ArinB/MSBA-CAData/raw/main/CA05/movies_recommendation_data.csv

Building a movie recommendation website which uses your Recommendation Engine at 
the back-end. 

Scenerio:
Imagine a user is navigating your recommendation website, and he/she encounters a movie named “The Post”.
The user is not sure if he/she wants to watch it, but its genres intrigue the user; he/she is curious about other 
similar movies.
The user scrolls down to the “More Like This” section to see what recommendations your recommendation website will make, and the back-end algorithmic gears begin to turn.
Your website sends a request to its back-end for the 5 movies that are most similar to The Post.
The backend has a recommendation data set exactly like ours.
It begins by creating the row representation (better known as a feature vector) for The Post, then it runs a program similar to the one below to search for 
the 5 movies that are most similar to The Post, and finally sends the results back to the user at your website.

Following is the genre information about the movie “The Post”
IMDB Rating = 7.2, Biography = Yes, Drama = Yes, Thriller = No, Comedy = No, Crime = No, Mystery = No, History = Yes

What recommendations he/she will see?

# Netflix-Movie-Recommendation-using-NLP

![content based vs collaborative](https://user-images.githubusercontent.com/25379742/105794143-69b28500-5f58-11eb-80f3-7b90745430d8.jpg)

There are two types of recommender systems:

1. Content-Based Filtering
This form of filtering is used to make recommendations based on similar products/services according to their attributes. For example, you have a movie that a user has already watched. Based on this information, we extract the features of this movie and use that information to find similar types of movies. The features could be anything such as the director of the movie, the actors in the movies, the plot, the genre, the language, etc. This type of filtering does not take into account other users, their likes or dislikes. Based on what we like, the algorithm will simply pick items with similar content to recommend us.

2. Collaborative filtering
This type of filtering is based on user ratings and consumption patterns to group similar users together, then use that information to recommend products/services to users based on users.  With the same example of movies that we mentioned above, a Collaborative filter will recommend movies that we haven’t watched yet, but users similar to us have watched and liked. This algorithm will basically recommend a movie for a user who hasn’t watched it yet, based on the similar users’ ratings. For understanding similarity between users, Collaborative filtering can lead to some problems like cold start for new items that are added to the list. Until someone rates them, they don’t get recommended. Basically, the idea is to find the most similar users to your target user (nearest neighbors) and weight their ratings of an item as the prediction of the rating of this item for target user.

This model that I have tried to showcase uses Content-based filtering since the data we are using does not involve any user information. 


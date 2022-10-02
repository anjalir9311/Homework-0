Music recommender system

One of the most used machine learning algorithms is recommendation systems. A recommender (or recommendation) system (or engine) is a filtering system which aim is to predict a rating or preference a user would give to an item, eg. a film, a product, a song, etc.

Which type of recommender can we have?

There are two main types of recommender systems: 

Content-based filters
Collaborative filters
Content-based filters predicts what a user likes based on what that particular user has liked in the past. On the other hand, collaborative-based filters predict what a user like based on what other users, that are similar to that particular user, have liked.

1) Content-based filters
Recommendations done using content-based recommenders can be seen as a user-specific classification problem. This classifier learns the user's likes and dislikes from the features of the song.

The most straightforward approach is keyword matching.

In a few words, the idea behind is to extract meaningful keywords present in a song description a user likes, search for the keywords in other song descriptions to estimate similarities among them, and based on that, recommend those songs to the user.

How is this performed?

In our case, because we are working with text and words, Term Frequency-Inverse Document Frequency (TF-IDF) can be used for this matching process.


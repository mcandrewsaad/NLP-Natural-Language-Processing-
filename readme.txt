project:
Create a new feature, called ‘n_tokens’ that counts how many tokens(words) there are in a review. 
In other words, a feature for the length of a review.
Create a new feature, called ‘language’, which detects what is the language of each review. 
So this feature will have a different value for each row (review) of the data.
Transform each review into a numeric vector of tokens using a bag-of-words. 
Use can use the CountVectorizer module from sklearn but limit the maximum number of features to be 1000 to avoid memory issues (you can decrease it further if you still have memory issues). Explore the other parameters of the function as well.
Using the fitted and transformed vector and the above created features, train a model that predicts the sentiment of a review. 
Evaluate your model and motivate your choice of a performance metric.



dataset:
2 txt.bz2 files
mixed data types
downloadable from this link:  https://www.kaggle.com/bittlingmayer/amazonreviews


work done:
cleanup, transformation, tokenization
NLP
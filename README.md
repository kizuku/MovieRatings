# MovieRatings
Try to predict binary user/movie ratings using various techniques and data files.

## Included Files

Data -- Folder containing data files

genome-scores.csv: movieid, tagid, relevance, indicating that for each movie-tag pair, the strength of this pair. Tags are user-generated metadata about movies. Each tag is typically a single word or short phrase. The meaning, value, and purpose of a particular tag is determined by each user.

genome-tags.csv: tagid, tag, indicating that each tagid coresponding to a specific tag.

kaggle_sample_submission.csv: a sample submission.

movies.csv: movieid, title, genres, indicating each movie's name and corresponding genres.

tags_shuffled_rehashed.csv: userId, movieId and tag, indicating that each user assigns a movie a tag.

test_ratings.csv: test dataset. Please follow the format of the sample submission to submit your answer to this test set.

train_ratings.csv: training dataset. It consists of three fields: userId, movieId, and rating (binary: 0 indicating dislike and 1 indicating like).

val_ratings.csv: validation dataset with the same fields as the training dataset.



Credit: The dataset is adapted from the MovieLens dataset with modifications, e.g. the user IDs are hashed and shuffled.


## Notes
Large data files are currently being stored with Git LFS.


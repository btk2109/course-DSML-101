use this dataset with the class:
K-Nearest Neigbours_Decision Tree_Naive Bayes_SVM
KNN: Recommendation Engine

in the code replace the local path to the file with this link:

# create the dataframe
r_cols = ['user_id', 'movie_id', 'rating']
# ratings = pd.read_csv('./movielens/u.data', sep='\t', names=r_cols, usecols=range(3)) # replace this line
ratings = pd.read_csv('./movielens/u.data', sep='\t', names=r_cols, usecols=range(3))
ratings.head()

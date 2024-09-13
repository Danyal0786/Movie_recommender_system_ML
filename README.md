# Movie_recommender_system_ML

## Dataset
The dataset that we are using here is the TMDB 5000 Movie Dataset. Under this dataset, there are 2 files:

1. tmdb_5000_movies.csv: It includes 20 columns like budget, genres, id, keywords, title, tagline, etc.
2. tmdb_5000_credtis.csv: It includes 4 columns- movie_id, title, cast, and crew.

We are using both of these datasets. You can download both of the datasets from here - https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv.

## Dump the file using pickle into your ipynb:
```python
pickle.dump(new_df.to_dict(),open('movies.pkl','wb'))
pickle.dump(similarity,open('similarity.pkl','wb'))

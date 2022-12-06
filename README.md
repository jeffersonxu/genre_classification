# Genre Classification
## Dataset
music_genre_raw.csv is the original, uncleaned csv file.\
music_genre_cleaned.csv is the csv file after we removed duplicate entries using Jupyter Notebook (clean_dataset.ipynb).\
music-genre-cleaned-2.csv is the final dataset cleaned using OpenRefine. We removed multiple columns ("artist_name", "index", "track_name") and songs with invalid tempo and duration.

## EDA
We performed exploratory data analysis (EDA) in eda.ipynb to see the distribution of the features and the relationship between these features and genre.

## Models
We ran a total of 5 models.
* Logistic Regression
* Random Forest
* KNN Classifier
* Decision Tree
* Ensemble - Bagging

These are included in ensemble.ipynb, logistic_regression.ipynb, random_forest.ipynb




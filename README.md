# imdb-movie-rating-prediction
Audible Data Science technical challenge - Movie Rating Prediction using IMDB Datasets

> Use the publicly available [IMDB Datasets](https://www.imdb.com/interfaces/) to build a model that predicts a movie’s average rating.
>
> [Read more](./Audible_DS_TakeHome.pdf)

<a target="_blank" href="https://colab.research.google.com/github/jyok117/imdb-movie-rating-prediction/blob/main/imdb_movie_rating_prediction.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

---

**Steps**:
1. Data Gathering
2. Data Preprocessing
    1. Load the data
    2. Merge datasets
    3. Filter the relevant data
    4. Handling null values
3. Exploratory Data Analysis
    1. Correlation plot
    2. Assumption 1. 'adult' movies tend to have slightly lower ratings
    3. Assumption 2. `averageRating` is normally distributed
    4. Assumption 3. `genres` affect the `averageRating`
4. Feature Engineering
    1. One-hot encoding of Genres
    2. Dimensionality reduction
5. Model Training and Evaluation
    1. Linear Regression
    2. Decision Trees
    3. Random Forests
    4. Random Forests (after parameter tuning)
6. Conclusion
    1. Who would use your model?
    2. What might they find surprising?
    3. How confident would you be in your model predictions?
    4. How does it align with Audible's People's Principles?

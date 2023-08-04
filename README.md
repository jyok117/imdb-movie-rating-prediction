# imdb-movie-rating-prediction
Audible Data Science technical challenge - Movie Rating Prediction using IMDB Datasets

---

Steps:
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

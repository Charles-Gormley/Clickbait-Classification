# Clickbait Classification

### Files
* **clickbait_data.csv**: CSV File received that has labeled clickbait articles. Originally Received from here: https://www.kaggle.com/datasets/amananandrai/clickbait-dataset 
* **logistic_regression.pkl**: The trained logistic regression model with ~98% accuracy on the testing dataset.
* **training.ipynb**: Jupyter Notebook that trained the logistic_regression model. Notebook loads in article data from AWS, vectorizes article titles, runs pca on vectors to see vector salience, runs multiple models with differing hyperparameter spaces using optuna to figure the best (and fastest) model. 

### How to use
* Gather a dataset of articles and their associated titles.
* Process with the titles with Google News' Word Vectorizer
* Load in the model *logistic_regression.pkl*
* Feed in the Vectorized titles as a pandas dataframe to obtain your classifications. 


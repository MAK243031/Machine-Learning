# Machine-Learning
Fake &amp; Real News
# Fake News Detection Project

This project aims to build a model that can accurately classify news articles as fake or real.

## Dataset

The dataset used for this project consists of two CSV files:

* `Fake.csv`: Contains fake news articles.
* `True.csv`: Contains real news articles.

## Methodology

1. **Data Loading and Preprocessing:**
   - Load the fake and real news datasets.
   - Merge the datasets and drop unnecessary columns.
   - Clean the text data by removing punctuation, special characters, and URLs.

2. **Feature Extraction:**
   - Use TF-IDF vectorization to convert text data into numerical features.

3. **Model Training:**
   - Train a Logistic Regression model and a Random Forest model on the training data.

4. **Model Evaluation:**
   - Evaluate the models' performance on the testing data using accuracy and classification report.

5. **Word Cloud Visualization:**
   - Create a word cloud to visualize the most frequent words in the dataset.

6. **Saving the Model:**
    - Save the trained models and vectorizer using `joblib` for later use.

## Usage

1. Load the saved model and vectorizer.
2. Preprocess the input text.
3. Vectorize the input text using the loaded vectorizer.
4. Use the loaded model to predict the class of the input text.

## Dependencies

* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* nltk
* wordcloud
* tensorflow
* joblib

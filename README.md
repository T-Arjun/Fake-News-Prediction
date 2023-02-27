# Fake-News-Prediction

# dependencies

This implementation uses the following dependencies:

    numpy
    pandas
    re
    nltk
    sklearn
    
# Data Preprocessing
  Importing necessary libraries
        numpy: For numerical operations
        pandas: For data manipulation and analysis
        re: For regular expressions used in text cleaning
        nltk.corpus: For accessing stopwords
        nltk.stem.porter: For stemming words
        sklearn.feature_extraction.text: For converting text to vectors
        sklearn.model_selection: For splitting data into training and testing sets
        sklearn.linear_model: For implementing logistic regression algorithm
        sklearn.metrics: For evaluating the model's accuracy

  Downloading stopwords
        The stopwords are words that occur frequently in text data but do not carry much meaning. These are removed from the text data during preprocessing to improve model accuracy.

    Printing the stopwords in English

    Loading the dataset
        The dataset is a csv file containing news articles and their labels (fake or real).

    Checking for null values
        The dataset contains null values which are replaced with empty strings.

    Merging author name and news title
        Author name and news title are combined to form the content of the news article.

    Preprocessing the text data
        Converting text to lowercase
        Removing non-alphabetic characters
        Removing stopwords
        Stemming words
        Converting text to vectors using TF-IDF vectorization

# Model Training

    Splitting the dataset into training and testing sets

    Training a Logistic Regression model on the training set

    Making predictions on the testing set

    Evaluating the accuracy of the model

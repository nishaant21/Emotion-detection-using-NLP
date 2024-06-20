# Emotion-detection-using-NLP

# Emotion Detection from Text

This project focuses on classifying emotions from text data using natural language processing (NLP) and machine learning techniques.

## Project Description

The goal of this project is to predict the emotion expressed in a given text. The emotions considered in this project are:
- Anger
- Fear
- Joy
- Love
- Sadness
- Surprise

## Dataset

The dataset used for this project is `emotion_nlp.csv`, which contains text data labeled with emotions.

## Project Workflow

1. **Data Loading and Preprocessing:**
   - Load the dataset into a pandas DataFrame.
   - Check for missing values.
   - Rename columns for easier handling.
   - Encode target labels (emotions) into numerical values.
   - Convert text data to lowercase and preprocess by removing punctuation and stopwords.

2. **Feature Extraction:**
   - Use a Bag-of-Words (BoW) model to transform text data into a term-document matrix (TDM) using `CountVectorizer`.

3. **Model Training and Evaluation:**
   - Split the data into training and test sets.
   - Train and evaluate multiple classifiers:
     - Multinomial Naive Bayes (NB)
     - Logistic Regression
     - Decision Tree Classifier
     - Random Forest Classifier
   - Generate confusion matrices and calculate the accuracy of each classifier.

## Results
The performance of the classifiers is evaluated using confusion matrices and accuracy scores. The accuracy of each classifier is compared to determine the best performing model for emotion detection.

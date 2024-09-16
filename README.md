# SMS-_Spam_Classifier

## Overview
This project is an SMS Spam Classifier that uses machine learning to detect and classify text messages as either spam or ham (not spam). The classifier is trained on a dataset of labeled SMS messages, and utilizes Natural Language Processing (NLP) techniques to process the text before applying a machine learning algorithm for classification.

## Features
1. Text Preprocessing: Cleans and prepares the SMS text for classification.
2. Feature Extraction: Uses techniques like TF-IDF (Term Frequency-Inverse Document Frequency) to extract features from text.
3. Classification Model: Implements a machine learning model (e.g., Naive Bayes, Logistic Regression, or Support Vector Machines) to classify the messages.
4. Evaluation: Evaluates model performance using accuracy, precision, recall, and F1-score.

## Dataset
The dataset used for training and testing the classifier consists of SMS messages that are labeled as either spam or ham. You can download a similar dataset from the [Here](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset).

## Project Structure

SMS-Spam-Classifier/
│
├── dataset/
│   └── spam.csv            # Dataset containing SMS messages with labels
│
├── src/
│   ├── preprocess.py        # Script for text preprocessing
│   ├── feature_extraction.py # TF-IDF and other feature extraction methods
│   ├── train.py             # Training the machine learning model
│   └── predict.py           # Script for making predictions on new messages
│
├── models/
│   └── spam_classifier.pkl  # Saved classifier model
│
├── notebooks/
│   └── EDA.ipynb            # Exploratory Data Analysis notebook
│
├── requirements.txt         # Python dependencies for the project
└── README.md                # Project description and instructions


## Prerequisites
To run this project, you will need:

Python 3.x
Install the required Python libraries by running

pip install -r requirements.txt

## Model Performance

The spam classifier achieves high accuracy on the test data, and the evaluation metrics (precision, recall, F1-score) indicate its effectiveness in identifying spam messages.

## Demo

You can try out the SMS spam classifier by running the streamlit run app.py script. Simply input a sample message, and the script will output whether the message is spam or ham.

## Contributions

Feel free to contribute by opening issues or submitting pull requests! Contributions that enhance the accuracy, performance, or features of the classifier are welcome.



# SMS/Email Spam Classifier Using Naive Bayes


This repository contains the implementation of an SMS/Email spam classification model using Natural Language Processing (NLP) techniques and the Naive Bayes algorithm. The project includes data exploration, preprocessing, model building, evaluation, and deployment using Streamlit for a simple web interface.

## Project Overview

The SMS/Email Spam Classifier project aims to classify messages as either 'spam' or 'ham' (not spam) using machine learning techniques. The classifier is built using the Naive Bayes algorithm, and the model is deployed using Streamlit to provide an interactive web application for users to test the classifier with their own messages.

![output](https://github.com/Sarathchandra1293/Spam-Detection-Using-Naive-Bayes/assets/99632999/ab358ed0-cd9d-41dc-a860-2268325fdb4b)


![output1](https://github.com/Sarathchandra1293/Spam-Detection-Using-Naive-Bayes/assets/99632999/127f9848-d520-4f73-943a-fece07dbaa63)

## Dataset

The dataset used in this project is the "SMSSpamCollection" dataset, which consists of a collection of SMS messages labeled as 'spam' or 'ham'. The dataset can be found in the `SMSSpamCollection.txt` file.

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) involves examining the dataset to understand its structure and main characteristics. Key steps include:
- Checking for null values and duplicates
- Visualizing the distribution of 'spam' and 'ham' messages
- Analyzing message lengths (characters, words, sentences)

## Data Preprocessing

Data preprocessing steps include:
1. Removing punctuation
2. Removing special characters
3. Removing stopwords
4. Lemmatizing words
5. Encoding labels to binary format

## Model Building

The model is built using the following steps:
- Applying TF-IDF Vectorizer to convert text data into numerical vectors
- Splitting the data into training and testing sets
- Training the Naive Bayes model on the training data

## Evaluation

The model is evaluated using the testing data. The evaluation metrics include:
- Accuracy Score
- Confusion Matrix
- Classification Report

The model achieved an accuracy score of 99% and a precision score of 97.5%.

## Deployment

The model is deployed using Streamlit, a Python library that allows for the creation of interactive web applications. The web app allows users to input messages and receive predictions on whether the message is 'spam' or 'ham'.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Sarathchandra1293/Spam-Detection-Using-Naive-Bayes/
    cd Spam-Detection-Using-Naive-Bayes
    ```

2. Run "Building a Spam Mail Detection Application.ipynb":
    ```python
    run this file in jupyter-notebook or vs-code or google-collab
    ```

3. Streamlit app:
    ```python
    pip install streamlit
    ```

## Usage

1. streamlit run spam_detector.py
2. Enter an SMS or email message in the text area.
3. Click the 'Predict' button to see if the message is classified as 'spam' or 'ham'.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or contact here [E-mail](sarathchandraedubelli@gmail.com)


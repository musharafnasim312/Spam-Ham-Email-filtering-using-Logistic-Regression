# Spam-Ham-Email-filtering-using-Logistic-Regression
Spam Ham Email filtering using Logistic Regression


**Introduction**
This project aims to develop and implement a machine learning model for filtering spam messages from non-spam (ham) messages. With the increasing volume of unsolicited and potentially harmful emails and messages, effective spam filtering has become a necessity for personal and professional email users. By leveraging the Logistic Regression algorithm, this project seeks to accurately classify messages, thereby improving the user experience and security.


**Goal**
The primary goal of this project is to design, train, and deploy a machine learning model that can accurately distinguish between spam and ham messages. By doing so, we aim to reduce the number of spam messages that reach users' inboxes, thus minimizing exposure to potentially fraudulent or harmful content. Additionally, we seek to maintain a low false-positive rate, ensuring that legitimate messages are not incorrectly classified as spam


**How i implement it?**

The project was implemented in several key steps.
Initially, we collected a dataset containing labeled messages as either spam or ham. The dataset underwent preprocessing to clean and prepare the text for modeling, including tokenization and normalization. We then utilized the Counter Vectorizer technique to convert the text data into a numerical format suitable for machine learning models. Following this, we chose the Logistic Regression algorithm for its efficiency and effectiveness in binary classification tasks. The model was trained on a portion of the dataset and evaluated using cross-validation to ensure its accuracy and robustness

**Counter Vectorizer**
The Counter Vectorizer is a critical component of our text preprocessing pipeline. It works by converting a collection of text documents into a matrix of token counts. Essentially, it breaks down the text into individual words (or tokens) and counts how often each word appears in each document. This process transforms the textual data into a numerical form that our Logistic Regression model can understand and learn from. By analyzing these counts, the model learns to associate certain word patterns with spam or ham classifications, enabling it to predict the category of new, unseen messages.


My spam-ham filtering project successfully demonstrates the application of Logistic Regression in classifying text messages

# sms_spam_detector
mod21
The goal of this project is to develop a model that can accurately classify SMS text messages as either spam or ham. The solution includes a Gradio web interface that allows users to enter an SMS message and get an immediate classification result.

Key Components:
Data Preprocessing:

The dataset used for training is SMSSpamCollection.csv, which contains SMS messages labeled as either "spam" or "ham".
The data is cleaned, with special attention paid to ensuring proper text formatting and label consistency.
Model Training:

A LinearSVC model is trained using TF-IDF vectorization on the SMS text.
The model is evaluated with 33% of the data reserved for testing.
Gradio Interface:

A Gradio-based app is developed to take user input in the form of an SMS message and classify it as spam or not spam.
The Gradio interface provides a simple and intuitive way for users to interact with the model.

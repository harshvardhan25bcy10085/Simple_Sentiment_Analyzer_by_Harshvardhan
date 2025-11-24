 Project Title:

Simple Sentiment Analysis Using Python & Machine Learning


 Overview:

This project is a beginner-friendly AI/ML-based Sentiment Analyzer that predicts whether a given sentence expresses a positive or negative sentiment. It uses a small custom dataset for training and applies basic Natural Language Processing (NLP) techniques. The model is trained using the Naive Bayes classifier, a simple and fast algorithm suitable for text classification.

The user can enter any sentence at runtime, and the system instantly returns the predicted sentiment along with the confidence score.


 Features:

 Classifies text into Positive or Negative sentiment

 Real-time prediction based on user input

 Uses the Bag-of-Words model for text processing

 Lightweight and easy to understand

 Perfect for first-year AI/ML mini-project submission

 No large datasets required


 Technologies / Tools Used:

Python 3

scikit-learn (Machine Learning)

CountVectorizer (NLP – Bag of Words)

Naive Bayes Classifier


 How the System Works:

A small dataset of positive and negative sentences is defined manually.

CountVectorizer converts text into numerical features (Bag-of-Words).

A Naive Bayes classifier is trained on this dataset.

User enters a sentence during runtime.

The model predicts the sentiment and displays:

sentiment label (Positive/Negative)

confidence score

🛠 Steps to Install & Run the Project
1. Install Python

Make sure Python 3.x is installed on your system.

2. Install required libraries

Open terminal / CMD and run:

pip install scikit-learn(If needed)

pip install numpy

3. Save the Project File

Create a file named:

sentiment_analyzer.py


Paste the project code inside it.

4. Run the project
python sentiment_analyzer.py

5. Enter sentences

Examples you can try:

I love this movie

This is the worst thing ever

I am feeling great today

 Instructions for Testing:

To thoroughly test the system:

Test positive phrases

“I really enjoyed this”

“This is amazing”

 Test negative phrases

“I hate this so much”

“This is a terrible experience”

 Test mixed or neutral phrases

“The food was okay”

“The class was normal”

 Edge cases

Empty input

Very long sentence

Sentences with slang

The classifier will try its best even with unknown words, based on learned patterns.


 Possible Improvements:

Add more training data for better accuracy

Build a GUI using Tkinter

Save the model using pickle

Add Neutral sentiment classification

Use advanced models like Logistic Regression or SVM


 Conclusion:

This project demonstrates how machine learning and simple NLP techniques can be used to classify text sentiment. It is lightweight, easy to understand, and ideal for beginners learning AI/ML concepts.
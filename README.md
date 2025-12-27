Instagram Review Sentiment Analysis
🔍 Project Overview

This project is an end-to-end NLP-based Sentiment Analysis system that analyzes Instagram user reviews/comments and classifies them into Positive, Neutral, or Negative sentiments.

The goal of this project is to demonstrate my understanding of Natural Language Processing (NLP), text preprocessing, class imbalance handling, and deep learning (LSTM) using Python.

🎯 Problem Statement

Social media platforms like Instagram generate a massive amount of user feedback. Manually analyzing these reviews is inefficient and time-consuming.

👉 This project automates the process by:

Cleaning raw Instagram review text

Extracting meaningful features

Training a deep learning model

Predicting sentiment accurately

🧠 Approach & Workflow

Data Loading

Loaded Instagram review dataset

Explored sentiment distribution

Text Preprocessing

Lowercasing

Removing punctuation & special characters

Tokenization

Padding sequences

Handling Class Imbalance

Applied class weights to handle uneven sentiment distribution

Model Building

Used LSTM (Long Short-Term Memory) neural network

Suitable for sequential text data

Model Training & Evaluation

Trained the model on processed data

Evaluated using accuracy and classification metrics

Sentiment Prediction

Final model predicts:

✅ Positive

😐 Neutral

❌ Negative

🏗️ Model Architecture

Embedding Layer

LSTM Layer

Dense Output Layer (Softmax)

📈 Results

Successfully classified Instagram reviews into 3 sentiment classes

Improved performance using class weighting

Model effectively captures sentiment patterns in user-generated text

#Training Accuracy = 87%
#Validation Accuracy = 86%

#loss: 0.56 →  0.36
#val_loss: 0.42 → 0.36

🛠️ Tech Stack

Language: Python

Libraries:

NumPy

Pandas

Scikit-learn

TensorFlow / Keras

NLTK / spaCy (if used)

Model: LSTM

Notebook: Jupyter Notebook

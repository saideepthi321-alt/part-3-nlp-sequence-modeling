# Part 3: NLP and Sequence Modeling Mini Project

## Project Overview

This project demonstrates a complete Natural Language Processing (NLP) pipeline for customer support sentiment classification.

The objective is to understand:
- how textual data is preprocessed
- how text is converted into numerical vectors
- how traditional NLP approaches compare with sequence-based deep learning models

The project uses a customer support dataset containing customer messages labeled with:
- positive
- neutral
- negative sentiments

Both traditional machine learning and sequence-based deep learning approaches are implemented and evaluated for sentiment classification.

# Objectives

The main objectives of this project are:

- Analyze and understand a text dataset
- Perform NLP preprocessing
- Convert text into numerical representations
- Build a baseline NLP classification model
- Build a sequence-based LSTM model
- Understand attention mechanisms and transformers
- Compare traditional NLP with deep learning approaches

# Task 1: Dataset Understanding

In this task, the customer support text dataset is loaded and analyzed.

The following analysis is performed:
- Number of records
- Dataset columns
- Target labels/classes
- Sample customer messages
- Average text length
- Class distribution visualization
This step helps in understanding the structure and balance of the dataset before applying NLP techniques.

# Task 2: Text Preprocessing

Text preprocessing is an important step in Natural Language Processing (NLP).

The raw customer messages are cleaned and transformed into a machine-readable format.

The following preprocessing steps are performed:
- Convert text to lowercase
- Remove special characters and symbols
- Tokenize text into words
- Remove stopwords
- Convert words into sequences
- Apply padding to create equal-length sequences

These processed sequences will later be used for traditional NLP models and sequence-based deep learning models.

# Task 3: Text Vectorization

Machine learning models cannot directly understand raw text data.

Therefore, text must be converted into numerical vectors before it can be used for training.

In this task, two vectorization approaches are used:

1. TF-IDF Vectorization
   - Represents text based on word importance
   - Commonly used in traditional NLP models

2. Tokenizer-Based Sequences
   - Converts words into integer sequences
   - Used in sequence models such as RNNs and LSTMs

These techniques help transform textual information into machine-readable numerical representations.


# Task 4: Baseline Model

A baseline NLP model is built using:
- TF-IDF vectorization
- Logistic Regression classifier

This model serves as a traditional machine learning approach for text classification.

The dataset is split into training and testing sets, and the model is evaluated using:
- Accuracy
- Classification Report
- Confusion Matrix

# Task 5: Sequence Model using LSTM

A sequence-based deep learning model is built using Long Short-Term Memory (LSTM) networks.

Unlike traditional NLP methods such as TF-IDF, sequence models preserve the order of words in a sentence.

The model architecture includes:
- Input sequence layer
- Embedding layer
- LSTM recurrent layer
- Dense output layer

The model demonstrates how sequence-based architectures process textual data while preserving contextual and sequential relationships between words.

# Task 6: Attention and Transformer Reflection

This section discusses:
- limitations of traditional RNNs
- how LSTMs improve memory handling
- the role of attention mechanisms
- the importance of transformers in modern NLP and Generative AI

The discussion explains how transformer-based architectures enable advanced language understanding and text generation in modern AI systems such as GPT and BERT.

# Results

The baseline Logistic Regression model using TF-IDF vectorization achieved strong classification performance on the dataset.

The LSTM sequence model demonstrated the concept of sequence learning and contextual text processing, though performance was limited due to:
- small dataset size
- limited training epochs
- simple model architecture

The project successfully demonstrates both traditional NLP workflows and sequence-based deep learning approaches for sentiment classification.

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

Both traditional machine learning and sequence modeling techniques are implemented and evaluated.

---

# Objectives

The main objectives of this project are:

- Analyze and understand a text dataset
- Perform NLP preprocessing
- Convert text into numerical representations
- Build a baseline NLP classification model
- Build a sequence-based LSTM model
- Understand attention mechanisms and transformers
- Compare traditional NLP with deep learning approaches

---

# Dataset Information

The dataset contains customer support messages and corresponding sentiment labels.

### Target Classes
- Positive
- Neutral
- Negative

### Important Columns
- `customer_message`
- `sentiment_label`
- `channel`
- `word_count`
- `urgent_flag`

---

# Project Structure

```text
part-3-nlp-sequence-modeling/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
└── results/
    ├── model_evaluation.png
    └── sample_predictions.txt

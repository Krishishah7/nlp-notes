# TF-IDF (Term Frequency–Inverse Document Frequency)

## What is TF-IDF?
TF-IDF is a statistical technique used to convert text into numerical features by measuring the importance of words in documents.

## Why It Is Used
- Reduces the impact of common words
- Highlights meaningful and distinctive terms
- Prepares text data for machine learning models

## How It Works (High Level)
- **TF (Term Frequency):** Measures how often a word appears in a document
- **IDF (Inverse Document Frequency):** Penalizes words that appear in many documents
- **TF-IDF = TF × IDF**

## Key Points
- Produces sparse numerical vectors
- Values represent relative importance, not probability
- Commonly combined with cosine similarity or classifiers

## Use Cases
- Text classification
- Text similarity
- Search engines
- Information retrieval

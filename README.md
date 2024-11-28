# Emotion Text Classification

This project focuses on classifying text comments into different emotions using machine learning techniques. The goal is to build a text classification model that can predict the emotion behind a given text comment. We utilize two machine learning models: Support Vector Machine (SVM) and Naive Bayes, to achieve the classification.

## Project Overview

### Data Preprocessing

- **Lowercasing**: All text data is converted to lowercase to ensure uniformity.
- **Stopword Removal**: Commonly used words (like "the", "and", etc.) are removed, as they do not contribute to meaningful information.
- **Punctuation Removal**: Punctuation marks are removed to clean the data.
- **Tokenization**: Text data is split into individual words or tokens.
- **Removal of Short Words**: Words that are too short (e.g., less than 3 characters) are removed.

### Feature Extraction

1. **Count Vectorization**:
   - Converts the text into a matrix of word counts.
   - Each feature in the matrix represents the frequency of a word in the document.

2. **TF-IDF Vectorization**:
   - This technique transforms the text data into a matrix of weighted word counts based on their importance.
   - The TF-IDF score helps to highlight the most relevant words in the dataset.

### Models Used

1. **Support Vector Machine (SVM)**:
   - Achieved **90% accuracy**.
   - SVM is a supervised learning model that works well with high-dimensional datasets like text data.
   
2. **Naive Bayes**:
   - Achieved **89% accuracy**.
   - A probabilistic classifier based on Bayes' theorem, which is particularly effective for text classification tasks.

### Results

- **SVM** achieved an accuracy of **90%** and an F1 Score of **0.91** (weighted).
- **Naive Bayes** achieved an accuracy of **89%** and an F1 Score of **0.90** (weighted).

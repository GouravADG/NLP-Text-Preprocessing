# NLP Text Preprocessing Project

## Overview

This project demonstrates the fundamental preprocessing techniques used in Natural Language Processing (NLP). The workflow includes cleaning and preparing text data for machine learning and text analysis tasks using Python.

The project uses the SMS Spam Collection dataset and applies several preprocessing steps to transform raw text into a structured format suitable for NLP applications.

---

## Features

- Reading and loading text datasets
- Punctuation removal
- Text tokenization
- Stopword removal
- Word stemming
- Word lemmatization
- Text preprocessing pipeline

---

## Project Structure

```text
NLP/
├── 1.Read the data.py
├── 2.Remove Punctuations.py
├── 3.Tokenization.py
├── 4.Remove Stopwords.py
├── 5.Stemming.py
├── 6.Lemmatizing.py
└── SMSSpamCollection.tsv
```

---

## Technologies Used

- Python
- NLTK (Natural Language Toolkit)
- Pandas
- Regular Expressions (Regex)

---

## Dataset

The project uses the SMS Spam Collection dataset, which contains labeled SMS messages categorized as spam or ham (non-spam).

---

## NLP Techniques Demonstrated

### 1. Reading Data
Loading and exploring the dataset.

### 2. Punctuation Removal
Removing special characters and punctuation marks from text.

### 3. Tokenization
Splitting sentences into individual words or tokens.

### 4. Stopword Removal
Removing common words that do not contribute significant meaning.

### 5. Stemming
Reducing words to their root form.

### 6. Lemmatization
Converting words into their meaningful base form using linguistic analysis.

---

## Installation

Install the required libraries:

```bash
pip install nltk pandas
```

---

## Running the Project

Execute the Python scripts in sequence:

```bash
python "1.Read the data.py"
python "2.Remove Punctuations.py"
python "3.Tokenization.py"
python "4.Remove Stopwords.py"
python "5.Stemming.py"
python "6.Lemmatizing.py"
```

---

## Applications

- Text Classification
- Spam Detection
- Sentiment Analysis
- Chatbots
- Machine Learning Pipelines
- Information Retrieval Systems

---

## Author

Gourav Sharma


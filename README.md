# Dravidian Stopword Analysis using NLP & Machine Learning

A multilingual NLP preprocessing project focused on stopword removal and text normalization for Dravidian languages including Telugu, Tamil, Kannada, and Malayalam using Python.

## Project Overview

This project implements a reusable NLP preprocessing pipeline for multilingual text processing tasks. The system performs:

- Tokenization
- Stopword Removal
- Text Normalization
- Basic Stemming

The project is designed to support preprocessing workflows for machine learning and natural language processing applications.

---

## Supported Languages

- Telugu
- Tamil
- Kannada
- Malayalam

---

## Features

- Multilingual stopword datasets
- Language-specific preprocessing
- Modular Python implementation
- Reusable preprocessing functions
- NLP pipeline for text analysis

---

## Technologies Used

- Python
- NLTK
- NLP
- Machine Learning Concepts

---

## Project Structure

```bash
├── preprocess.py
├── stopwords.py
├── main.py
├── README.md
└── requirements.txt


---

## Installation

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

```python
from stopwords import preprocess_text

result = preprocess_text(
    "ఇది నా తెలుగు పరిశోధన ప్రాజెక్ట్",
    "telugu"
)

print(result)
```

---

## Sample Output

```python
{
    'tokens': ['ఇది', 'నా', 'తెలుగు', 'పరిశోధన', 'ప్రాజెక్ట్'],

    'after_stopword_removal': ['తెలుగు', 'పరిశోధన', 'ప్రాజెక్ట్'],

    'after_stemming': ['తెలుగు', 'పరిశోధన', 'ప్రాజెక్ట్']
}
```

---

## Applications

- NLP Pipelines
- Text Preprocessing
- Sentiment Analysis
- Multilingual Text Analytics

---

## Future Improvements

- Add more regional language datasets
- Improve stemming and lemmatization
- Integrate ML-based text classification
- Build a web-based NLP interface

---

## Author

Sanjana Gorli  
B.Tech CSE | IITM BS Data Science  

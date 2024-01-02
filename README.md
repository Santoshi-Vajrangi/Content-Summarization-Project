# Text Summarization using Spacy

This repository contains code for text summarization using SpaCy, a natural language processing library in Python. The Jupyter Notebook demonstrates the process of text cleaning, tokenization, frequency analysis, and extractive summarization.

## Process Overview

- **Text Cleaning:** The code starts by cleaning the provided text, removing stopwords and punctuation for further analysis.
- **Tokenization:** Utilizing SpaCy, the text is tokenized into words and sentences for processing.
- **Word Frequency Analysis:** The code computes word frequencies and normalizes them between 0 and 1 to identify important words.
- **Sentence Tokenization:** Sentences are tokenized to analyze their importance in the context of word frequency.
- **Sentence Scoring:** Each sentence is scored based on the frequency of important words it contains.
- **Summary Generation:** The code uses an extractive method to generate a summary by selecting the top-scoring sentences.

## Dependencies

The code utilizes SpaCy and Python's standard libraries for text processing and analysis.

## Usage

To run the code, execute the Jupyter Notebook provided (`Text_summarization.ipynb`) in a compatible environment with SpaCy installed.

## Results

The code generates an extractive summary based on word frequencies and sentence scores, condensing the provided text into a shorter form for easier understanding.

Feel free to explore, modify, or enhance the text summarization process based on your requirements.

# Text Cleaning and Analysis Project

This project focuses on cleaning, preprocessing, and analyzing text data. It covers various steps to process raw text and evaluate the quality of the cleaned data using automated metrics like readability scores and lexical diversity.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Workflow](#workflow)
  - [1. Data Loading](#1-data-loading)
  - [2. Preprocessing](#2-preprocessing)
  - [3. Automated Metrics](#3-automated-metrics)
  - [4. Text Normalization](#4-text-normalization)
- [Outputs and Metrics](#outputs-and-metrics)
- [Runtime](#runtime)
- [License](#license)

---

## Features
1. **Data Loading**:
   - Load and merge datasets.
   - Analyze the initial number of documents and statistics.

2. **Preprocessing**:
   - Tokenize text into sentences and words.
   - Remove URLs, special characters, spaces, numbers, account mentions, and phone numbers.
   - Normalize text to lowercase.

3. **Automated Metrics**:
   - **Readability Scores**:
     - Use Flesch-Kincaid readability grade to ensure the text is interpretable.
   - **Lexical Diversity**:
     - Measure the richness of vocabulary as the ratio of unique words to total words.

4. **Text Normalization**:
   - Remove stopwords.
   - Apply lemmatization and stemming for text simplification.

---

## Technologies Used
- Python 3.8+
- Libraries: 
  - `pandas`
  - `nltk`
  - `re`
  - `textstat`
  - `time`

---



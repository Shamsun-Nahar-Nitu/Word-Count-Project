# Word Count Analysis Project

## Overview
This project is a Python-based text processing pipeline built in a Jupyter Notebook. It demonstrates how to read multiple text documents, clean and preprocess the text, and perform frequency analysis. The project uses a MapReduce-style approach to count words, generate n-grams, and visualize the most prominent terms using a Word Cloud.

## Features
* **Automated Text Cleaning:** Converts text to lowercase, strips punctuation, removes standalone numbers, and filters out common English "stopwords" (e.g., "the", "is", "and") using NLTK.
* **Overall & Per-File Word Counts:** Analyzes all text collectively while also providing a specific top-word breakdown for each individual text file in the directory.
* **N-Gram Analysis:** Generates bigrams (two-word pairs) to find common contextual phrases (e.g., "machine learning", "big data").
* **Data Visualization:** Automatically generates a high-quality Word Cloud image highlighting the most frequently used terms.
* **CSV Export:** Saves the final compiled word frequency data into an organized CSV file for further analysis or reporting.

## Prerequisites
To run this notebook, you will need Python installed along with the following libraries:
* `pandas`
* `matplotlib`
* `nltk`
* `wordcloud`

Required libraries using pip:
```bash
pip install pandas matplotlib nltk wordcloud
```
Project Structure
```
Word-Count-Project/
│
├── Word Count.ipynb       # The main Jupyter Notebook containing the code
├── README.md              # Project documentation
├── folder/                # Directory containing input .txt files
│   ├── file1.txt          
│   ├── file2.txt          
│   └── file3.txt          
└── output/                # Directory generated automatically for outputs
    └── word_count.csv     # The exported word frequency data
```

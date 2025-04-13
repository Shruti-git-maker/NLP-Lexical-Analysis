# NLP-Lexical-Analysis
LexicalAnalysis.ipynb
Overview
This Jupyter Notebook, 17Nov_NLP2_LexicalAnalysis.ipynb, provides an in-depth exploration of lexical analysis techniques used in Natural Language Processing (NLP). It demonstrates various steps involved in breaking down text into its fundamental components, such as tokens, stems, and lemmas, while also analyzing word patterns and frequencies.

Features
The notebook covers the following key topics and techniques:

Lexical Analysis Concepts:

Definitions of morphemes, tokens, and lexemes.

Explanation of lexical analysis as the process of breaking down text into basic units.

Steps in Lexical Analysis:

Tokenization (using NLTK and Regular Expressions).

Stopword removal.

Stemming and Lemmatization.

Canonicalization techniques.

Bag of Words (BoW) and TF-IDF (conceptual introduction).

Practical Implementations:

Tokenization using NLTK's word_tokenize and regular expressions.

Word frequency analysis using Python's collections.Counter.

Stopword removal using NLTK's stopwords.

Stemming with PorterStemmer.

Lemmatization with WordNetLemmatizer.

Dependencies
The following Python libraries are required to run this notebook:

nltk: For tokenization, stopword removal, stemming, and lemmatization.

re: For regular expressions.

collections: For counting word frequencies.

Installation
To install the required libraries, run:

bash
pip install nltk
Usage Instructions
Clone or download the notebook file to your local machine.

Open the notebook in Jupyter Notebook or Google Colab.

Run the cells sequentially to observe the output of each step.

Key Sections
Tokenization: Demonstrates splitting text into individual words using both NLTK and regular expressions.

Stopword Removal: Filters out common words like "is," "and," etc., which carry little semantic meaning.

Stemming vs. Lemmatization:

Stemming: Reduces words to their root forms (e.g., "running" → "run").

Lemmatization: Converts words to their dictionary forms (e.g., "running" → "run").

Example Input Text
The notebook uses a sample text on NLP concepts for demonstration:

Natural language processing (NLP) is a subfield of computer science and especially artificial intelligence...

Example Outputs
Tokenized Words:
['Natural', 'language', 'processing', '(', 'NLP', ')', ...]

Filtered Tokens (After Stopword Removal):
['Natural', 'language', 'processing', 'NLP', 'subfield', ...]

Stemmed Tokens:
['natur', 'languag', 'process', 'nlp', 'subfield', ...]

Lemmatized Tokens:
['Natural', 'language', 'processing', 'NLP', 'subfield', ...]

Notes
The notebook includes examples of handling special cases like punctuation removal and part-of-speech tagging during lemmatization.

The importance of stopword filtering is highlighted using Zipf's power law.

Future Improvements
Add advanced canonicalization techniques like TF-IDF implementation.

Extend examples to include named entity recognition (NER) or dependency parsing.

License
This project is open-source and available under the MIT License.

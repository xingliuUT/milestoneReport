# Text Data Cleaning and N-Grams Analysis

## Background
This is for Coursera Data Science Capstone Project. The goal is to build predictive text models that predict the next word based on the previously entered words. 

This project uses the natural language processing and text mining tools used in R to clean, tokenize, and conduct exploratory analysis on the large text data sets. 

Text data used in this project includes English texts from news, blogs and twitter which are offered by the company [SwiftKey](https://swiftkey.com/en) in the format of HC Corpora. Plans of how to build the text model will also be discussed.

## Report
The report is available [on line](http://rpubs.com/xl3676/276955).

## Method

### Cleaning
Remove profanity words, numbers, remove punctuation, strip white spaces, convert to all lower cases letters.

### Compute 1-gram, 2-gram, 3-gram frequencies
Term-document matrix is used to find word (1-gram) frequencies.

Generate 2-gram and 3-gram with `tokenize_ngrams` function from `tokenizers` package.

## Source code
The source code is in the file `report.Rmd`.

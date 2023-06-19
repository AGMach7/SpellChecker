# Spell Checker

Welcome to Spell Checker, an intelligent and versatile spell checking tool for the English language!

## Overview

Spell Checker is designed to help you find and correct spelling mistakes in your text using advanced language modeling techniques. It offers three powerful approaches to improve the accuracy of spell checking:

1. **Unigram-based Spell Checker**: Leverages a unigram language model to suggest corrections for misspelled words. It analyzes the context and frequency of words in the English language to provide the most likely alternatives.

2. **Template-based Spell Checker**: Introduces a template language model that combines language model probabilities and minimum edit distance to order the suggested corrections. This approach helps prioritize more contextually relevant corrections.

3. **Letter Sequence Language Model Spell Checker**: Employs a cutting-edge language model that models the distribution of letter sequences instead of words. This approach enables the spell checker to handle complex misspellings and provide accurate suggestions.

## Dataset

To train our language models, we used the `en_US_twitter.txt` dataset. This corpus consists of real-world English text from Twitter, capturing the nuances and variations of informal language usage.

## Getting Started

To get started with Spell Checker, follow the instructions in the provided .ipynb (Jupyter Notebook) file. Each approach is explained in detail, and code cells are provided for easy execution and experimentation.

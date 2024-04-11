# Fake News Detection with Machine Learning

This project demonstrates how to build a fake news detection system using web scraping, natural language processing (NLP), and machine learning. The system utilizes Selenium for web scraping, NLTK for text preprocessing, and scikit-learn for building a logistic regression model.

## Overview

The goal of this project is to preprocess the text data, and classify the articles as either "real" or "fake" using a trained logistic regression model. The workflow includes the following steps:

1. **Text Preprocessing**: Clean and preprocess the article text using NLTK, including tasks like removing HTML tags, converting to lowercase, removing non-alphabetic characters, removing stopwords, and stemming.
3. **Model Training**: Utilize scikit-learn to train a logistic regression model on a labeled dataset of news articles.
4. **Prediction**: Scrape a new article, preprocess its text, transform it using TF-IDF, and predict its label (real or fake) using the trained model.

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/fake-news-detection.git
cd fake-news-detection

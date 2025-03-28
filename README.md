# Sentiment Analysis of Electric Vehicles in Indonesia

## 📌 Overview
This project focuses on **Sentiment Analysis of Electric Vehicles (EVs) in Indonesia** using machine learning models, specifically:
- **Logistic Regression**
- **Support Vector Machine (SVM)**

The goal is to classify sentiments from YouTube comments regarding EV adoption in Indonesia.

## 📂 Project Structure
This project consists of:

1. **Code**
   - **Data Collection:** Scraping YouTube comments related to EV discussions.
   - **Preprocessing:**
     - Case folding
     - Cleaning (removing unnecessary characters, URLs, etc.)
     - Stemming
     - Stopword removal
   - **Feature Extraction:**
     - TF-IDF (Unigram & Bigram)
   - **Sentiment Labeling:**
     - Using **NLTK VADER** with a customized lexicon.
   - **Model Training & Evaluation:**
     - Logistic Regression & SVM classification.
     - Performance analysis using accuracy, precision, recall, and F1-score.

## 🚀 Technologies & Frameworks
- **Python** (pandas, numpy, seaborn, scikit-learn)
- **Natural Language Processing** (NLTK, TF-IDF)
- **Machine Learning** (Logistic Regression, SVM)
- **Web Scraping** (YouTube API, Selenium/BeautifulSoup)

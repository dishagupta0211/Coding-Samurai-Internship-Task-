# Twitter Sentiment Analysis using NLP and Machine Learning

## 📖 Project Overview

Social media platforms generate massive amounts of user opinions every day. Understanding these opinions can help businesses, organizations, and researchers make data-driven decisions.

This project uses Natural Language Processing (NLP) and Machine Learning techniques to automatically classify tweets into sentiment categories. The model analyzes tweet text and predicts whether the sentiment expressed is Positive, Negative, or Neutral.

The project demonstrates the complete NLP workflow, including text preprocessing, feature extraction, model training, evaluation, and sentiment prediction.

---

## 🎯 Problem Statement

The objective of this project is to build a machine learning model capable of identifying the sentiment of a tweet based on its textual content.

### Sentiment Classes

- Positive 😊
- Negative 😞
- Neutral 😐

This is a **Multi-Class Text Classification Problem**.

---

## 📂 Dataset Information

The dataset contains tweets collected from social media platforms.

### Features

- Tweet Content
- Sentiment Label

### Target Variable

```text
Positive
Negative
Neutral
```

---

## ⚙️ Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- NLTK
- Regular Expressions (re)
- Scikit-Learn
- Matplotlib
- Seaborn
- WordCloud
- Pickle

---

## 🧹 Text Preprocessing

Raw tweets often contain noise such as URLs, special characters, hashtags, and unnecessary symbols.

The following preprocessing steps were performed:

### 1. Convert Text to Lowercase

Standardizes the text format.

### 2. Remove URLs

Eliminates unnecessary links from tweets.

### 3. Remove Special Characters

Removes punctuation and symbols.

### 4. Remove Numbers

Filters out numerical values that do not contribute to sentiment.

### 5. Tokenization

Splits text into individual words.

### 6. Stopword Removal

Removes commonly used words that add little meaning.

Examples:

```text
the
is
am
are
was
were
```

### 7. Text Cleaning

Produces clean and meaningful text for model training.

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Sentiment Distribution
- Class Balance Analysis
- Word Frequency Analysis
- Word Cloud Visualization
- Most Frequent Positive Words
- Most Frequent Negative Words

These analyses helped understand the dataset before model training.

---

## 🔤 Feature Extraction

Machine learning algorithms cannot directly process text.

Therefore, textual data was converted into numerical representations using:

### TF-IDF Vectorization

Term Frequency – Inverse Document Frequency (TF-IDF) measures the importance of words within the dataset.

Benefits:

- Reduces importance of common words
- Highlights informative words
- Improves model performance

---

## 🤖 Machine Learning Model

The following algorithm was used:

### Logistic Regression

Reasons for choosing Logistic Regression:

- Efficient for text classification
- Fast training time
- Good performance on sparse TF-IDF features
- Easy interpretation

---

## 📈 Model Training Pipeline

```text
Raw Tweets
     ↓
Text Cleaning
     ↓
Tokenization
     ↓
Stopword Removal
     ↓
TF-IDF Vectorization
     ↓
Train-Test Split
     ↓
Logistic Regression
     ↓
Prediction
```

---

## 📊 Model Evaluation

The model was evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

## 🏆 Results

### Final Accuracy

```text
~80%
```

The model successfully classified tweet sentiments with good overall performance and demonstrated the effectiveness of combining NLP preprocessing with machine learning techniques.

---

## 💾 Model Saving

The trained model and vectorizer were saved using Pickle.

### Saved Files

```text
sentiment_model.pkl
tfidf_vectorizer.pkl
```

These files allow future predictions without retraining the model.

---

## 🚀 Future Improvements

Potential improvements include:

- Hyperparameter Tuning
- Advanced Text Cleaning
- N-Gram Features
- Deep Learning Models (LSTM, GRU)
- Transformer Models (BERT)
- Real-Time Twitter Data Analysis
- Web Application Deployment

---

## 📌 Project Workflow

1. Data Collection
2. Data Exploration
3. Text Preprocessing
4. Feature Extraction using TF-IDF
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Model Saving
9. Sentiment Prediction

---

## 💡 Key Learning Outcomes

Through this project, the following concepts were learned:

- Natural Language Processing (NLP)
- Text Cleaning Techniques
- Stopword Removal
- TF-IDF Vectorization
- Machine Learning Classification
- Model Evaluation
- Model Serialization using Pickle

---

## 👩‍💻 Author

**Disha Gupta**

Computer Science Engineering Student

Skills:
- Python
- SQL
- Machine Learning
- Data Analytics
- Natural Language Processing (NLP)

---

## ⭐ If you found this project useful, consider giving it a star.

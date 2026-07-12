# 💬 Sentiment Analysis using Machine Learning

## 📌 Project Overview

This project focuses on building a Machine Learning model to classify text into **Positive**, **Negative**, and **Neutral** sentiments. It demonstrates the complete Natural Language Processing (NLP) pipeline, including text preprocessing, feature extraction using TF-IDF, model training, evaluation, and visualization.

The project was completed as part of the **Oasis Infobyte Data Analytics Internship – Task 4**.

---

## 🎯 Objective

To develop a sentiment classification model that analyzes textual data and predicts whether the sentiment is **Positive**, **Negative**, or **Neutral**, helping businesses understand customer opinions and improve decision-making.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- WordCloud
- Jupyter Notebook

---

## 📂 Dataset

**Dataset:** Twitter Entity Sentiment Analysis

The dataset contains tweets categorized into:
- Positive
- Negative
- Neutral
- Irrelevant (removed during preprocessing)

---

## 📊 Project Workflow

### 1. Data Loading
- Imported dataset
- Checked dataset dimensions
- Examined missing values
- Removed irrelevant records

### 2. Text Preprocessing
- Converted text to lowercase
- Removed URLs
- Removed punctuation
- Removed numbers
- Removed stopwords
- Lemmatized words
- Created cleaned text column

### 3. Feature Extraction
- Applied TF-IDF Vectorization
- Converted text into numerical feature vectors

### 4. Model Training
Two machine learning models were trained:

- Naive Bayes
- Logistic Regression

### 5. Model Evaluation

Evaluation metrics used:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 6. Data Visualization
- Sentiment Distribution
- Confusion Matrix
- WordCloud (Positive)
- WordCloud (Negative)
- WordCloud (Neutral)
- Model Accuracy Comparison

### 7. Error Analysis
Displayed incorrectly classified tweets to understand model limitations.

---

## 📈 Results

| Model | Accuracy |
|--------|----------|
| Naive Bayes | 71.62% |
| Logistic Regression | 75.71% |

**Best Model:** Logistic Regression

---

## 📁 Project Structure

```
DataAnalytics-L4-SentimentAnalysis/
│
├── Sentiment_Analysis.ipynb
├── twitter_training.csv
├── cleaned_sentiment_dataset.csv
├── README.md
├── requirements.txt
└── images/
    ├── sentiment_distribution.png
    ├── confusion_matrix_nb.png
    ├── confusion_matrix_lr.png
    ├── positive_wordcloud.png
    ├── negative_wordcloud.png
    ├── neutral_wordcloud.png
    └── model_accuracy.png
```

---

## 📷 Project Output

### Sentiment Distribution

![Sentiment Distribution](images/sentiment_distribution.png)

---

### Logistic Regression Confusion Matrix

![Confusion Matrix](images/confusion_matrix_lr.png)

---

### Positive WordCloud

![Positive WordCloud](images/positive_wordcloud.png)

---

### Negative WordCloud

![Negative WordCloud](images/negative_wordcloud.png)

---

### Neutral WordCloud

![Neutral WordCloud](images/neutral_wordcloud.png)

---

## 🚀 Real-World Applications

- Customer Feedback Analysis
- Product Review Classification
- Brand Reputation Monitoring
- Social Media Analytics
- Public Opinion Analysis
- Market Research
- Customer Experience Improvement

---

## 📌 Conclusion

This project demonstrates how Natural Language Processing and Machine Learning can automatically classify textual data into different sentiment categories. Among the evaluated models, **Logistic Regression achieved the best performance**, making it suitable for practical sentiment analysis applications.

---

## 👩‍💻 Author

**Jayshri Borude**

Data Analytics Intern – Oasis Infobyte


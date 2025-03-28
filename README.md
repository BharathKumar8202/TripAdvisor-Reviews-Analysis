# Problem 3: Text Mining & Sentiment Analysis of Hotel Reviews 🏨💬

## 🧠 Overview  
Transform unstructured hotel reviews into clear, actionable insights! In this problem, we mine text data and perform sentiment analysis using the Multinomial Naive Bayes classifier.

---

## 📦 What's Inside

### 📊 Data & EDA
- Work with 20,000 real-world hotel reviews.
- Checked for null values, duplicates, and explored rating distributions.
- Visualized review length and rating frequencies.

### 🧹 Text Preprocessing
- Removed punctuation, stopwords, and special characters.
- Converted text to lowercase and applied lemmatization.
- Transformed text data using **TF-IDF** vectorization.

### 🤖 Modeling
- Applied **Multinomial Naive Bayes** for classification.
- Evaluated model performance using accuracy, confusion matrix, and classification report.
- Tackled class imbalance using **SMOTE** oversampling.

### 😄 Sentiment Analysis
- Used **VADER** from NLTK to compute sentiment scores.
- Created 4 sentiment metrics: Positive, Negative, Neutral, and Compound.
- Visualized sentiment distribution and frequency of most-used words.

---

## 🖼️ Visual Snapshots

### ☁️ Word Clouds  
#### Positive Reviews 🌟  
<img src="images/positivereviewss.png" alt="Word Cloud - Positive Sentiment" width="400"/>

#### Negative Reviews ⚠️  
<img src="images/negativereviews.png" alt="Word Cloud - Negative Sentiment" width="400"/>

🧠 Built with Python, NLTK, Scikit-learn, and WordCloud.  

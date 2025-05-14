# 🌌 Text Mining & NLP – Star Wars Trilogy Scripts

This project applies Natural Language Processing (NLP) techniques to analyze the original Star Wars movie scripts (Episodes IV–VI). Using Python and NLTK, the project explores character dialogue patterns, frequency distributions, word clouds, TF-IDF scores, and sentiment analysis.

---

## 🎯 Objectives

- Extract and analyze dialogue frequency by character
- Perform preprocessing (tokenization, stopword removal, lemmatization)
- Analyze word frequency before and after text cleaning
- Generate word clouds for Darth Vader and Yoda
- Identify most relevant words using **TF-IDF**
- Conduct sentiment analysis to compare Sith vs Jedi dialogue tone

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `v24kucha-Lab 04.ipynb` | ✅ Main notebook with full text mining process |
| `star_wars_movies_scripts.ipynb` | 📄 Supporting script / EDA |
| `Lab4 Instructions - (Text Mining & NLP).pdf` | 📜 Original lab assignment details |
| `star_wars_movies_scripts-checkpoint.ipynb` | Auto-save backup file |

---

## 🧠 Key NLP Techniques Used

- Frequency distribution using `FreqDist`
- Text cleaning:
  - Lowercasing
  - Tokenization
  - Stopword removal
  - Lemmatization
- TF-IDF vectorization
- Word cloud generation (masked)
- Sentiment analysis using `VADER`

---

## 📊 Visualizations

- 📈 Dialogue frequency plots per episode
- ☁️ Word clouds for **Darth Vader** and **Yoda**
- 🧠 TF-IDF scores for high-impact words
- 😊😠 Sentiment scores comparing Light Side vs Dark Side

---

## 🔍 Tools & Libraries

- `NLTK`  
- `matplotlib`, `seaborn`  
- `wordcloud`, `PIL`  
- `scikit-learn` (`TfidfVectorizer`)  
- `vaderSentiment`  
- `re`, `string`  

---

## ✨ Insights

- Characters like **Luke**, **Leia**, **Vader**, and **Yoda** dominate dialogue across episodes.
- Jedi characters (Yoda, Luke) show more **positive sentiment**, while Sith characters (Vader, Palpatine) exhibit **negative tone**.
- Word clouds visually highlight the dominant language styles of each faction.

---



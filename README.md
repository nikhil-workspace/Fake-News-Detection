# 📰 Fake News Detection

This project uses Natural Language Processing (NLP) to classify news articles as **Fake** or **Real**.

---

## 🎯 Objective
Build a text classification model to detect fake news using logistic regression and naive bayes.

---

## 📂 Dataset
- Source: [Fake and Real News Dataset on Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
- Combined: `Fake.csv` + `True.csv`
- Shape: ~44K articles

---

## ⚙️ Preprocessing
- Lowercasing
- Removing punctuation
- Stopword removal (NLTK)
- TF-IDF Vectorization with bigrams (`ngram_range=(1,2)`, `min_df=5`, `max_df=0.7`)

---

## 🧠 Models Used
| Model              | Accuracy | AUC Score |
|-------------------|----------|-----------|
| Logistic Regression | ~99%     | Very High |
| Naive Bayes         | ~98%     | Very High |

---

## 📊 Evaluation Metrics
- Confusion Matrix
- Classification Report (Precision, Recall, F1)
- ROC-AUC Curve

Both models performed exceptionally well, with Logistic Regression slightly outperforming.

---

## 📁 Project Structure

fake-news-detection/
│
├── Fake.csv
├── True.csv
├── fake_news_detector.ipynb
├── README.md
└── requirements.txt


---

## 💡 Skills Demonstrated
- Text Preprocessing (NLP)
- TF-IDF Feature Engineering
- Binary Classification Models
- Evaluation using ROC-AUC & Confusion Matrix

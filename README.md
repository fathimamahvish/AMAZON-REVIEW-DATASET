# 🧠 Sentiment Analysis on Amazon Product Reviews

This project performs **Sentiment Analysis** on Amazon product reviews to determine whether a review expresses a **Positive**, **Negative**, or **Neutral** sentiment.  
This helps businesses understand **customer satisfaction**, **common pain points**, and **improvement opportunities**.

---

## 🔍 Project Overview

Sentiment analysis uses **Natural Language Processing (NLP)** techniques to interpret human emotions from text.  
In this project, we:
- Preprocessed real customer reviews
- Used **VADER (Valence Aware Dictionary and sEntiment Reasoner)** from NLTK
- Classified text into **Positive / Negative / Neutral**
- Visualized sentiment patterns
- Generated insights for decision-making

---

## 📂 Dataset

**Dataset Name:** `amazon_reviews_dataset.csv`  
Contains 15+ customer reviews with ratings.

| Column | Description |
|--------|-------------|
| Review | The text content of the customer's review |
| Rating | Numeric rating (1 to 5) |

---

## 🛠️ Tools & Technologies

| Tool / Library | Purpose |
|----------------|---------|
| Python | Core Programming |
| Pandas | Data Loading & Processing |
| NLTK (VADER) | Sentiment Detection |
| Matplotlib | Bar Chart Visualization |
| WordCloud | Text Visualization |

---

## 🚀 How to Run the Project

### 1. Install Dependencies
```bash
pip install pandas numpy nltk matplotlib wordcloud

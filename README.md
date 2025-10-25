# 🧠 Hate Speech Detection using NLP and Machine Learning

## 📘 Overview
This project detects **hate speech in tweets** — specifically identifying **racist or sexist content** — using **Natural Language Processing (NLP)** and **Machine Learning (ML)**.  
It’s a **binary text classification** problem:  
- `1` → Hate Speech (racist/sexist)  
- `0` → Non-Hate (normal/love)

---

## ⚙️ Approach
1. **Data Cleaning** – Removed URLs, mentions, hashtags, punctuation, and stopwords.  
2. **Text Preprocessing** – Tokenization, lowercasing, and stemming using NLTK.  
3. **Feature Extraction** – Used **TF-IDF vectorization** (top 5000 terms).  
4. **Model Training** – Trained 5 ML models:
   - Logistic Regression  
   - Naive Bayes  
   - Linear SVM  
   - Random Forest  
   - Gradient Boosting  
5. **Evaluation** – Compared accuracy and visualized performance using bar charts.

---

## 📊 Results
- Achieved strong performance with **Logistic Regression and Linear SVM** as top models.  
- Created **WordClouds** to visualize frequent words in hate vs. non-hate tweets.

---

## 🧩 Tools & Libraries
`Python`, `Pandas`, `Scikit-learn`, `NLTK`, `Matplotlib`, `WordCloud`, `TF-IDF`

---

## 💡 Key Takeaway
This project demonstrates how **NLP and ML** can help automatically detect and mitigate **hate speech on social media**, promoting safer online communication.

---

## 📁 Files
- `train.csv` – Training dataset  
- `test.csv` – Test dataset  
- `hate_speech_detection.ipynb` – Main code file  
- `README.md` – Project documentation

---

## ✨ Author
**Khurram Rashid**  
📍 Amity University Mumbai  
🔗 [LinkedIn](https://www.linkedin.com/in/khurram-rashid/) | [GitHub](https://github.com/KhurramRashid6893)

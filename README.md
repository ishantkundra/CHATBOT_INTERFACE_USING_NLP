# 🧠 Capstone Project – NLP Chatbot for Industrial Safety Risk Classification and Recommendation

## 📌 Project Overview

This Capstone Project focuses on building an **intelligent chatbot interface** for handling and classifying accident descriptions using **Natural Language Processing (NLP)** and **Deep Learning** techniques. It serves both as a **classification system** for industrial safety incidents and an interactive **chatbot application** built with **Flask**.

---

## 🏭 Domain: Industrial Safety & Health

Organizations often struggle with analyzing textual accident descriptions. This project automates the classification of such reports and provides a chatbot that interacts with users in real time for accurate and fast classification.

---

## 🎯 Objectives

- Clean and process real-world accident description data
- Classify accidents using ML & DL models
- Train deep learning models using **LSTM** and **Word2Vec**
- Build and deploy a **chatbot** interface that allows users to input descriptions
- Provide real-time predictions through a **Flask web app**

---

## 📦 Dataset

- `industrial_safety_and_health_database_with_accidents_description.csv`  
  Contains accident descriptions and labeled classifications

### Key Features:
- `Accident Level`
- `Potential Accident Level`
- `Injury Type`
- `Accident Description` (free-text)
- Other workplace and injury metadata

---

## 🛠️ Project Components

### ✅ Data Preprocessing
- Lowercasing, tokenization
- Stopword removal, stemming
- Vectorization using **TF-IDF** and **Word2Vec**

### ✅ Modeling
- Classical ML models: Logistic Regression, SVM
- Deep Learning: RNN with LSTM layers
- Word Embeddings: **Word2Vec**, **GloVe**
- Evaluation using precision, recall, F1-score

### ✅ Chatbot Interface
- Built with **Flask** web framework
- User inputs free-form text
- Back-end processes and classifies input
- Returns real-time predictions via trained model

### ✅ UI Integration
- Input form for user interaction
- Model predictions shown with description classification
- Clean Bootstrap-based frontend

---

## ⚙️ Tools, Libraries & Skills Used

- **Languages:** Python, HTML/CSS (Flask frontend)
- **NLP:** NLTK, spaCy, Gensim
- **Deep Learning:** TensorFlow, Keras
- **ML Models:** Logistic Regression, SVM
- **Word Embeddings:** Word2Vec, GloVe
- **Web:** Flask, OpenCV (used for UI enhancements)
- **Visualization:** Matplotlib, Seaborn

---

## 📁 Repository Structure

<pre>
.
├── code/
│   └── Capstone Project - Group 3 - NLP Chatbot Interface-Milestone-Final.ipynb
│
├── dataset/
│   ├── Data Set - industrial_safety_and_health_database_with_accidents_description.csv
│   └── Data Set - industrial_safety_and_health_database_with_accidents_description.xlsx
│
├── Problem statement/
│   └── AIML Capstone Project - NLP chatbot.pdf
│
├── Report/
│   └── Capstone Report Format_June22B_NLP ChatBot_Final.pdf
│
├── README.md
└── .gitignore
</pre>

---

## 💡 Key Learnings

- Built an end-to-end **NLP pipeline** for classifying industrial accident data  
- Trained and compared multiple models with traditional and deep learning approaches  
- Gained experience in **Word Embedding** techniques like Word2Vec and GloVe  
- Integrated deep learning models into a **working chatbot UI**  
- Learned deployment best practices using **Flask** and Python for NLP interfaces

---

## ✍️ Author

**Ishant Kundra**  
📧 [ishantkundra9@gmail.com]
🎓 Master’s in Computer Science | AIML Track

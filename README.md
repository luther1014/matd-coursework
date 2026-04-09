# 📚 Methods of Textual Data Analysis – Coursework Repository

This repository contains a collection of assignments and implementations developed as part of the *Methods of Textual Data Analysis* course.  
The goal of this repository is to demonstrate fundamental techniques used in **Natural Language Processing (NLP)** and **Information Retrieval (IR)** through hands-on implementations.

---

## 🚀 Overview

The project focuses on building core NLP and IR components **from scratch**, with an emphasis on understanding underlying algorithms rather than relying on high-level libraries.

Topics covered include:
- Text preprocessing and tokenization
- Statistical language modeling
- String matching algorithms
- Information retrieval systems
- Vector space representations

---

## 📂 Implemented Assignments

### 🔤 Byte Pair Encoding (BPE) Tokenizer
- Implemented both **word-level and byte-level BPE**
- Demonstrates subword tokenization used in modern NLP models
- Explores merge operations and vocabulary construction

---

### ✍️ Automatic Word Correction
- Based on probabilistic approaches (inspired by Norvig’s algorithm)
- Uses:
  - Edit distance (Levenshtein distance)
  - Word frequency from corpus
- Suggests most likely corrections for misspelled words

---

### 🔎 Pattern Matching Algorithms
- Implementations include:
  - **Brute Force**
  - **Knuth-Morris-Pratt (KMP)**
  - **Boyer-Moore-Horspool**
- Comparison of:
  - Time complexity
  - Number of character comparisons
  - Performance on different datasets

---

### 📊 N-gram Language Models
- Implemented:
  - **Unigram**
  - **Bigram**
  - **Trigram**
- Features:
  - Probability estimation
  - Sentence generation / prediction
  - **Perplexity evaluation**
- Includes smoothing techniques (e.g., Laplace smoothing)

---

### 🔍 Boolean Information Retrieval System
- Built a search engine using:
  - **Inverted index**
  - Boolean queries: `AND`, `OR`, `NOT`
- Includes:
  - Query parsing (Shunting-yard algorithm)
  - Efficient document retrieval

---

### 📈 TF-IDF Vector Space Model
- Implemented document ranking using:
  - **Term Frequency (TF)**
  - **Inverse Document Frequency (IDF)**
- Supports:
  - Cosine similarity
  - Ranked retrieval of documents

---

## 🛠️ Tech Stack

- **Python**
- Libraries:
  - `numpy`
  - `scipy`
  - `matplotlib`
  - `nltk`

---

## 📊 Key Learning Outcomes

Through this repository, the following concepts were explored:

- How modern NLP tokenization works (BPE)
- Probabilistic reasoning in language models
- Trade-offs between different string matching algorithms
- Design of search engines using inverted indices
- Ranking documents using vector space models

---

## 📌 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/textual-data-analysis.git
cd textual-data-analysis

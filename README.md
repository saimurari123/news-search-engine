# 📰 News Search Engine

A **Python-based news search engine** that crawls top newspapers, extracts articles, and allows keyword-based search using **TF-IDF and cosine similarity**. Built using a Colab notebook, this project demonstrates **web crawling, information retrieval, and text processing** techniques.

---

## 🌟 Features

- Crawl top news websites:
  - The Hindu
  - Times of India
  - BBC
  - Deccan Chronicle
- Extract and preprocess article text
- Build an **inverted index** for efficient keyword search
- Rank articles using **TF-IDF + cosine similarity**
- Display **top matching news articles with URLs**
- Fully implemented in a single **Colab notebook**

---

## 🧠 How It Works

1. **Crawling**  
   Collects web pages from selected news websites and stores them locally.

2. **Text Extraction & Preprocessing**  
   - Extracts article content from HTML  
   - Tokenizes text and removes stopwords  
   - Converts text to lowercase and filters out non-alphanumeric characters

3. **Inverted Indexing**  
   Maps each keyword to the documents that contain it for fast retrieval.

4. **Query Processing & Search**  
   - Preprocesses user query  
   - Retrieves candidate documents using the inverted index  
   - Computes relevance scores using TF-IDF and cosine similarity  

5. **Result Ranking**  
   Returns top-ranked articles with **source URLs** and **number of matched keywords**.

---

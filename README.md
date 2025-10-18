# Real-Time Fake News Detection

## About the Project
**Real-Time Fake News Detection** is an AI-powered application designed to classify news articles as **Real** or **Fake** in real time.  
It leverages **Deep Learning techniques** to understand textual content and detect misleading information, helping users and organizations quickly verify news credibility.

The system integrates **Natural Language Processing (NLP)** with a **LSTM-based neural network** and **pre-trained word embeddings** to analyze the semantic meaning of news articles. A **Gradio web interface** allows interactive, user-friendly predictions in real time.

This project can be used for:  
- Fact-checking news articles automatically  
- Educational purposes in AI and NLP  
- Research on misinformation and fake news detection  

---

## Features
- **Real-time prediction** of news articles as Real or Fake  
- **Confidence visualization** for each prediction  
- **Interactive web interface** via Gradio  
- **Text preprocessing** including tokenization, stopword removal, and sequence padding  
- Supports **custom news input** from users  

---

## Dataset
The model is trained on a **Kaggle dataset** containing labeled examples of real and fake news articles.  
- **Source:** [Kaggle Fake News Dataset](https://www.kaggle.com/c/fake-news/data)  
- Each article is preprocessed to remove noise and tokenized for embedding  
- Dataset includes thousands of news articles covering multiple domains  

---

## Model Architecture
- **Embedding Layer:** Uses **pre-trained GloVe embeddings** to convert words into meaningful vectors  
- **LSTM Layer:** Captures temporal relationships in text sequences  
- **Dense Layers:** Fully connected layers for classification  
- **Output Layer:** Sigmoid activation to predict Real (0) or Fake (1)  

---

## Tech Stack / Libraries
- Python  
- TensorFlow / Keras (for deep learning)  
- Numpy, Pandas (data manipulation)  
- NLTK / SpaCy (text preprocessing)  
- Gradio (web interface for interactive predictions)  

---

## Installation
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/fake-news-detection.git

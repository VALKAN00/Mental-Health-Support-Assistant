# 🧠 Mental Health Support Assistant

An **AI-powered system** designed to provide accessible and supportive guidance for mental well-being.  
This project was developed as my **Graduation Project** during my **Summer Training at the National Telecommunication Institute (NTI)** under the supervision of **Eng. Anas**.  

The assistant leverages **Natural Language Processing (NLP)** and **Machine Learning** techniques to analyze text input, detect potential mental health conditions, and provide empathetic, resource-driven responses through a **Telegram bot**.

---

## 🚀 Features
- **Fine-Tuned BERT Model**  
  Achieves **92.6% accuracy** in classifying text into seven mental health categories:  
  *Normal, Depression, Suicidal, Anxiety, Stress, Bi-Polar, Personality Disorder*.
  
- **Real-Time Resource Retrieval**  
  Uses DuckDuckGo Search API to fetch credible mental health resources from `.org` websites.

- **Generative Advice with LLaMA**  
  Provides safe, empathetic, and context-aware guidance using LLaMA (via Together AI).

- **Telegram Bot Integration**  
  A secure, user-friendly conversational interface for real-time support.

---

## 🗂️ Dataset & Preprocessing
The system was trained on a combined dataset curated from multiple public sources, including:  
- Depression Reddit Cleaned  
- Suicidal Tweet Detection  
- Human Stress Prediction  
- Student Anxiety & Depression Dataset  
- Bipolar & Personality Disorder Data  

**Preprocessing steps included:**  
- Cleaning (duplicates, special chars, URLs, case normalization)  
- Label encoding  
- Class balancing (RandomOverSampler)  
- Train/test split (80/20 stratified)  
- Tokenization with `bert-base-uncased`  

---

## 📊 Model Performance
| Epoch | Val Loss | Accuracy | F1 Score | Precision | Recall |
|-------|----------|----------|----------|-----------|--------|
| 1     | 0.2279   | 91.5%    | 91.3%    | 91.6%     | 91.5%  |
| 2     | 0.2228   | **92.6%**| **92.4%**| **92.5%** | **92.6%** |

---

## 🛠️ Tech Stack
- **Python**  
- **Hugging Face Transformers** (BERT)  
- **PyTorch**  
- **scikit-learn**  
- **DuckDuckGo Search API (ddgs)**  
- **LLaMA via Together AI**  
- **Telegram Bot API**  

---

# 🤖 AI Chatbot using Transformers (DialoGPT)

## 📌 Overview

This project demonstrates how to build a conversational AI chatbot using **Transformer-based models**.
The chatbot leverages **Microsoft DialoGPT**, a pre-trained language model designed for human-like conversations.

---

## 🎯 Objective

* Build an interactive chatbot using NLP techniques
* Understand how transformer models generate responses
* Learn conversational AI using pre-trained models

---

## 🛠️ Tech Stack

* Python 🐍
* Hugging Face Transformers 🤗
* PyTorch 🔥
* Google Colab

---

## ⚙️ Model Details

* Model: `microsoft/DialoGPT-medium`
* Type: Causal Language Model
* Use Case: Multi-turn conversation

---

## 🚀 Features

* Interactive chat loop
* Context-aware responses
* Human-like text generation
* Easy to extend and customize

---

## 🔄 Workflow

```id="a8f7n1"
User Input → Tokenization → Model Processing → Response Generation → Output
```

---

## 💬 Sample Conversation

**User:** Hi
**Bot:** Hello! How can I assist you today?

**User:** What is AI?
**Bot:** AI stands for Artificial Intelligence, enabling machines to simulate human thinking.

---

## 🧠 How It Works

1. User input is tokenized using a tokenizer
2. Input is passed to the DialoGPT model
3. Model generates a response based on context
4. Output is decoded and displayed

---

## ▶️ Installation

```bash id="4zv78r"
pip install transformers torch
```

---

## ▶️ Run the Project

Open the notebook and run all cells:

```bash id="y6p2dl"
jupyter notebook Task2.ipynb
```

---


## ⚠️ Limitations

* May generate irrelevant responses sometimes
* Limited long-term context memory
* Depends on pre-trained data

---

## 🚀 Future Improvements

* Fine-tune chatbot on custom dataset
* Add web interface (Streamlit)
* Deploy as REST API
* Improve conversational memory

---


# 📝 Text Summarization System using Fine-Tuned Transformers

![Python](https://img.shields.io/badge/Python-3.11-blue)
![NLP](https://img.shields.io/badge/NLP-Transformers-brightgreen)
![HuggingFace](https://img.shields.io/badge/HuggingFace-BART-yellow)
![Gradio](https://img.shields.io/badge/Gradio-Deployed-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)
![Domain](https://img.shields.io/badge/Domain-NLP-red)

---

## 🔍 Project Overview

A **fine-tuned Transformer-based Text Summarization system** that generates concise and context-aware summaries from long text inputs.

Unlike basic implementations, this project uses a **custom fine-tuned BART model**, improving performance on domain-specific data.

It simulates real-world use cases such as:
- News summarization  
- Business report summarization  
- Customer feedback analysis  

---

## 🏢 Business Problem

Organizations deal with massive amounts of text data:
- 📄 Articles  
- 📊 Reports  
- 💬 Customer reviews  

Challenges:
- ⏳ Time-consuming to read  
- 📉 Information overload  
- ❌ Hard to extract key insights  

This system helps:
- ⚡ Quickly summarize large documents  
- 🧠 Extract key insights  
- 📈 Improve productivity and decision-making  

---

## 🧠 ML Objective

Generate:
- High-quality abstractive summaries  
- Context-aware and human-like text  
- Reduced length while preserving meaning  

---

## 🧾 Input

- Long text / article / document  

---

## 🚀 Features

- ✨ Fine-tuned transformer model  
- 🧠 Domain-specific summarization  
- ⚡ Fast inference using optimized model  
- 📉 Reduces text length effectively  
- 🌐 Interactive Gradio web interface  
- 📊 Clean and structured output  

---

## 🛠 Technology Stack

- Frontend: Gradio  
- Backend: Python  
- NLP: Hugging Face Transformers  
- Model: Fine-tuned BART (`facebook/bart-large-cnn`)  
- Libraries: PyTorch, Datasets, Pandas  
- Deployment: Gradio / Hugging Face Spaces  

---

## 📊 NLP Pipeline

Dataset → Preprocessing → Tokenization → Fine-Tuning → Model Evaluation → Inference → Deployment

---

## 🧹 Data Preprocessing

- Text cleaning  
- Tokenization using BART tokenizer  
- Padding & truncation  
- Train-test split  

---

## 🤖 Model

### 📊 Base Model
- **BART (Bidirectional and Auto-Regressive Transformers)**  
- `facebook/bart-large-cnn`

### 🔥 Fine-Tuning

- Trained on **custom dataset**
- Learned domain-specific summarization patterns
- Improved summary quality compared to base model

---

## ⚙️ Training Details

- Framework: Hugging Face Trainer API  
- Batch Size: 8 
- Epochs: 2

---

## 📈 Inference Logic

- Input text is tokenized  
- Passed to fine-tuned BART model  
- Summary generated using `generate()` method  

---

## 🖥️ Gradio App Features

- Text input box for long content  
- One-click summarization  
- Instant output display  
- Clean and minimal UI  
- Supports real-time interaction  

---

## 📸 Screenshots

### 🏠 Home Page
![Home](https://github.com/anjalivarun13/Text-Summarization-System/blob/main/Screenshot/AI%20text%20summarization%20app%20ss1.png)

### 🎯 Summary Output
![Output](https://github.com/anjalivarun13/Text-Summarization-System/blob/main/Screenshot/AI%20text%20summarization%20app%20ss2.png)

---

## 🎬 Video Demo

[[Watch Demo]](https://streamable.com/u7l9h6)

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/text-summarization.git
cd text-summarization
python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate  # Mac/Linux
pip install -r requirements.txt
python app.py
```
---

## 🔮 Future Improvements
- Add multi-language summarization
- Fine-tune on larger datasets
- Add PDF/document upload feature
- Optimize inference speed
- Deploy using FastAPI + Docker

---

## 👩‍💻 Author

**Anjali Varun**

GitHub: https://github.com/anjalivarun13

LinkedIn: https://www.linkedin.com/in/anjali-varun/

# LLMs
# Large Language Models (LLMs) – Hands-On NLP Projects

## 📖 Introduction

This repository comprises a collection of **hands-on Jupyter notebooks** showcasing practical applications of **Large Language Models (LLMs)** and modern **transformer architectures** across core Natural Language Processing (NLP) tasks.

The goal is to provide **clear, code-first examples** of how LLMs and pre-trained transformer models can be used for:
- Text generation  
- Text classification  
- Question answering  
- Emotion detection  

Large Language Models are neural networks trained on massive text corpora that excel at language understanding and generation. Transformers, the architectural backbone of LLMs, rely on **self-attention mechanisms** to model contextual relationships effectively across diverse NLP applications.

---

## 📁 Repository Structure

| File | Description |
|-----|------------|
| **GPT Models.ipynb** | Prompt-based text generation using GPT-style LLMs |
| **HuggingFace Transformers.ipynb** | Introduction to transformer models using Hugging Face |
| **Question and Answering Models with BERT.ipynb** | Extractive question answering using BERT |
| **Text Classification with XLNet.ipynb** | Text classification using XLNet |
| **Emotion Label.ipynb** | Emotion-level text classification |

---

## 🚀 Running the Notebooks

### 1. Clone the Repository
```bash
git clone https://github.com/iamkarandeepsingh/LLMs.git
cd LLMs
python3 -m venv .venv
source .venv/bin/activate    # macOS / Linux
.venv\Scripts\activate       # Windows
pip install torch transformers numpy jupyter openai
jupyter notebook

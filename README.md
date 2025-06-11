# 🧠 Text Summarization Bot using Deep Learning (PEGASUS, BERT, SAMSum)

This project implements a real-time, intelligent **Text Summarization Bot** using state-of-the-art NLP models such as **PEGASUS** and **BERT**. Trained on the **SAMSum corpus**, this bot supports abstractive summarization, customizable summary length and style, multi-language support, and can summarize multiple documents at once. Designed with scalability in mind, it is also suitable for deployment on AWS.

## 🚀 Features

- 🔍 **Abstractive Summarization** using `PEGASUS` (Transformer-based model)
- 🔠 **Multilingual Support** for summarizing non-English inputs
- 🧩 **Customizable Summaries** (length, style, highlights)
- 📑 **Multi-Document Input** support
- 🔄 **Real-time Summarization** for dynamic content
- 💬 **Interactive Web UI** using Gradio
- ☁️ **Cloud Deployment Ready** (AWS EC2, Lambda, etc.)

---

## 📚 Architecture

The bot uses a transformer-based architecture (Google's PEGASUS model) fine-tuned on the [SAMSum Dataset](https://huggingface.co/datasets/samsum). It is equipped with an encoder-decoder mechanism for abstractive text generation.

---

## 🧪 Sample Output

![Screenshot 2025-06-12 002217](https://github.com/user-attachments/assets/58707717-de32-4aec-9d50-6054cf577eb0)

## ⚙️ Tech Stack

- `Python`
- `Transformers (HuggingFace)`
- `Gradio` (for Web UI)
- `Torch` (for model inference)
- `AWS` (for cloud deployment)

---


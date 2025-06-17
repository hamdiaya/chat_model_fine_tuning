# 🧠 Fine-Tuning LLaMA 3.1-8B with QLoRA using Unsloth

This repository contains my experiment in fine-tuning the `unsloth/Meta-Llama-3.1-8B-Instruct-bnb-4bit` model using the [QLoRA](https://arxiv.org/abs/2305.14314) technique on the [`pookie3000/pg_chat`](https://huggingface.co/datasets/pookie3000/pg_chat) dataset. The goal is to build a better understanding of how to fine-tune Large Language Models (LLMs) effectively using low-rank adaptation and 4-bit quantization.

> 🚀 This is a step in my learning journey in LLM fine-tuning and experimentation with lightweight, memory-efficient methods.

---

## 📚 Dataset

- **Source**: [`pookie3000/pg_chat`](https://huggingface.co/datasets/pookie3000/pg_chat)
- A chat-based dataset suitable for conversational AI fine-tuning.

---

## 🛠 Model

- **Base**: [`unsloth/Meta-Llama-3.1-8B-Instruct-bnb-4bit`](https://huggingface.co/unsloth/Meta-Llama-3.1-8B-Instruct-bnb-4bit)
- **Framework**: [Unsloth](https://github.com/unslothai/unsloth)
- **Technique**: QLoRA (Quantized Low-Rank Adaptation)

---

## 🔧 Features

- Fine-tuning with 4-bit quantization (bnb) for efficiency.
- LoRA adapters to reduce training cost and memory usage.






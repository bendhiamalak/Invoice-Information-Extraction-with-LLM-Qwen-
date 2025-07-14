# 🧾 Invoice Information Extraction with LLM (Qwen)

This project demonstrates how to use a large language model (LLM) to extract structured data (like invoice number, total, client info, etc.) from a raw invoice text using a defined Pydantic schema.

---

## 📌 Project Overview

We use the following tools and libraries:
- 🤗 **HuggingFace Transformers** to load the pretrained LLM (`Qwen2.5-1.5B-Instruct`)
- 🐍 **Pydantic** for defining and validating the structured schema of invoice data
- 🚀 **Google Colab** for execution
- 🔐 **HuggingFace** and **Weights & Biases (wandb)** tokens for authentication

---

## ✅ Features

- Extract structured fields from plain invoice text
- Validate extracted data with `Pydantic`
- Supports fine-tuned instruction-following LLMs (Qwen, Mistral, etc.)
- Token-based authentication for secure access

---




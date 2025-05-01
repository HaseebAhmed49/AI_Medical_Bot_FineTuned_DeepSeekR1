# 🧠 AI Medical Assistant – Fine-Tuning Guide

This project fine-tunes a powerful open-weight LLM (`DeepSeek-R1-Distill-Llama-8B`) using [Unsloth](https://github.com/unslothai/unsloth), to serve as a **clinical expert assistant**. It enables real-time medical question-answering using domain-specific prompts on Google Colab with 4-bit quantization.

---

## 📁 Project Structure

| Section               | Description                                              |
|-----------------------|----------------------------------------------------------|
| 📦 Setup              | Installs dependencies and checks for GPU                 |
| 🔐 Hugging Face Login | Authenticates to download the model                      |
| 🧠 Load LLM           | Loads a quantized version of LLaMA via Unsloth           |
| 🧪 Prompt Design      | Creates a tailored prompt for medical tasks              |
| ⚙️ Inference          | Performs real-time medical query generation              |

---

## ✅ Features

- 🏥 Designed for clinical diagnostics & treatment reasoning  
- ⚡ Fast and optimized loading using `Unsloth`  
- 🧩 Custom prompt style for expert-level answers  
- 💡 Real-time inference with medical queries  
- 🔐 Private token-based access using Hugging Face  

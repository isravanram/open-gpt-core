# open-gpt-core

# GPT From Scratch  
🎯 A professional-grade, minimal GPT implementation in **PyTorch** — built from first principles for research, learning, and experimentation.  

---

## 📌 Overview
This repository contains a clean and well-documented implementation of **Generative Pre-trained Transformers (GPT)** from scratch.  
Instead of abstracting away the details, every layer is carefully implemented to **expose the mechanics** of modern LLMs.  

The project is designed for:
- 🧑‍💻 **Engineers** who want a practical understanding of GPT internals.  
- 🎓 **Students/Researchers** exploring Transformers and language modeling.  
- 🚀 **Practitioners** building custom LLM architectures or experimenting with training.  

---

## 🧠 Core Architecture
This implementation covers the essential components of GPT-style Transformers:  
- **Token & Positional Embeddings** — combining word meaning with sequence order  
- **Multi-Head Self-Attention** — contextual relationships between tokens  
- **Causal Masking** — ensuring autoregressive prediction  
- **Feed-Forward Networks (FFN)** — non-linear transformations  
- **Residual Connections & Layer Normalization** — stabilizing training  
- **Stacked Transformer Blocks** — scalable depth  
- **Final Projection Layer** — mapping embeddings back to vocabulary space  

A **text generation pipeline** is also included with support for:
- Temperature scaling  
- Top-k sampling  
- End-of-sequence handling  

---

## 🚀 Features
- ✅ Minimal yet **production-quality** PyTorch code  
- ✅ Modular design for extending blocks and experimenting  
- ✅ Pretrained GPT weight loading support  
- ✅ Text generation with temperature & top-k sampling  
- ✅ Fully documented classes and functions  
- ✅ Easily extensible for training on custom datasets  

---

## 📦 Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/gpt-from-scratch.git
cd gpt-from-scratch
pip install -r requirements.txt


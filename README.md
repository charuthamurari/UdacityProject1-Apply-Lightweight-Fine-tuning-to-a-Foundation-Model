# Parameter-Efficient Fine-Tuning with Hugging Face PEFT (LoRA)

Lightweight fine-tuning is a crucial technique for adapting large foundation models to specific tasks without requiring massive computational resources.  
In this project, we apply **Parameter-Efficient Fine-Tuning (PEFT)** using the **Hugging Face `peft` library** to fine-tune a pre-trained model and compare its performance with the original.

---

## 📌 Project Overview

This project demonstrates:

- Loading and evaluating a **pre-trained foundation model**.
- Applying **LoRA (Low-Rank Adaptation)** using the Hugging Face `peft` library.
- Performing **training and inference** with the fine-tuned model.
- Comparing the **performance** of the original and fine-tuned models.

---

## 🛠 Key Concepts

- **PEFT (Parameter-Efficient Fine-Tuning)**: Fine-tunes a small set of parameters instead of the entire model.
- **LoRA (Low-Rank Adaptation)**: A PEFT technique that injects trainable rank decomposition matrices into the Transformer architecture.
- **Hugging Face `peft` library**: Provides an easy interface for creating and training PEFT models.

---


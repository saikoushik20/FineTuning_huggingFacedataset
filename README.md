# FineTuning_huggingFacedataset
# Emotion Classifier with DistilBERT

This project is a **text-based emotion classification model** built using Hugging Face Transformers and the [`dair-ai/emotion`](https://huggingface.co/dair-ai/emotion) dataset. The model can predict emotions like **joy, sadness, anger, fear, love, and surprise** from input text.

---

## Features

- Fine-tuned **DistilBERT** for emotion classification.
- Supports **single sentence prediction** and batch predictions.
- Evaluation using **accuracy** and **F1-score**.
- Easy to reproduce in **Google Colab**.

---

## Dataset

- Source: [`dair-ai/emotion`](https://huggingface.co/dair-ai/emotion) on Hugging Face Hub.
- Split: **train, validation, test**
- Labels: `joy`, `sadness`, `anger`, `fear`, `love`, `surprise`

---

## Installation

Install required libraries:

```bash
pip install -U transformers datasets pandas scikit-learn

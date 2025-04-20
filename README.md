# DL Assignment 2 — Sequence Models & GPT-2 Fine-tuning

This repository contains code and documentation for Deep Learning Assignment 2 under the course **22CAC04 - Deep Learning** at CBIT.

## 🔥 Assignment Goals

### Question 1: Sequence-to-Sequence Transliteration
- Build a seq2seq model using RNNs to transliterate between Latin and Devanagari scripts.
- Flexible architecture supporting:
  - Character-level embeddings
  - Choice of RNN / GRU / LSTM cells
  - Variable embedding size, hidden size, and layers
- Evaluated on the [Dakshina dataset](https://github.com/google-research-datasets/dakshina).
- Computes:
  - Total number of operations
  - Total number of parameters
- Reports accuracy and outputs on test set.

### Question 2: Fine-tuning GPT-2 for Lyrics Generation
- Cleaned and combined lyrics of Khalid and Lady Gaga
- Fine-tuned GPT-2 using Hugging Face Transformers and Datasets libraries
- Evaluated by generating sample lyrics from a custom prompt

## 📦 Requirements
- `torch`, `transformers`, `datasets`, `pandas`, `sklearn`
- Recommended: Google Colab or a machine with GPU

## 🚀 How to Run

1. Clone the repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt


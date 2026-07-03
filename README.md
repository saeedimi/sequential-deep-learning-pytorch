# Natural Language Processing with PyTorch

A collection of practical **Natural Language Processing (NLP)** projects implemented using **PyTorch**. This repository explores recurrent neural networks, language modeling, text generation, and sequence classification through hands-on implementations of RNNs, LSTMs, and generative language models. Each notebook has been reorganized, documented, and expanded to demonstrate practical deep learning workflows for NLP.

---

# 🚀 Repository Overview

This repository contains practical NLP projects built with **PyTorch**, covering recurrent neural networks, sequence modeling, text generation, and text classification using modern deep learning techniques.

<p align="center">
  <img src="Images/RNN_LSTM.jpg" width="750">
</p>

---

# ✨ Project Highlights

- Recurrent Neural Networks (RNNs)
- Long Short-Term Memory (LSTM) Networks
- Text Classification
- Character-Level Language Modeling
- Text Generation
- Sequence Modeling
- Word Embeddings
- TorchText
- GPU-ready PyTorch implementations
- Well-documented notebooks suitable for learning and experimentation

---

# 📚 Topics Covered

- Natural Language Processing (NLP)
- Recurrent Neural Networks (RNNs)
- Long Short-Term Memory (LSTMs)
- Sequence Modeling
- Character-Level Language Models
- Text Generation
- Text Classification
- Teacher Forcing
- Word Embeddings (GloVe)
- Variable-Length Sequences
- TorchText
- Deep Learning with PyTorch

---

# 🛠️ Technologies

- Python
- PyTorch
- TorchText
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn

---

# 📂 Repository Structure

```text
natural-language-processing-pytorch/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   ├── 01_recurrent_neural_networks.ipynb
│   ├── 02_generative_rnn.ipynb
│   └── 03_spam_detection_lstm.ipynb
│
├── Images/
│   └── RNN_LSTM.jpg
│
└── models/
```

---

# 📖 Notebooks

## Notebook 1 — Recurrent Neural Networks for Text Classification

### Overview

This notebook introduces recurrent neural networks for natural language processing using PyTorch. It explains how RNNs process variable-length text sequences, incorporates pre-trained GloVe word embeddings, and demonstrates text classification using recurrent architectures.

### Topics Covered

- Recurrent Neural Networks (RNNs)
- Text classification
- Variable-length sequences
- Sequence batching
- Hidden states
- GloVe word embeddings
- PyTorch implementation

### Notebook

`notebooks/01_recurrent_neural_networks.ipynb`

---

## Notebook 2 — Generative Recurrent Neural Networks

### Overview

This notebook extends recurrent neural networks to character-level language modeling and text generation. It demonstrates autoregressive sequence generation, teacher forcing during training, probability-based token sampling, and GPU-accelerated training for generative RNNs.

### Topics Covered

- Character-level language modeling
- Generative RNNs
- Text generation
- Teacher forcing
- Token sampling
- Hidden state propagation
- GPU training
- PyTorch implementation

### Notebook

`notebooks/02_generative_rnn.ipynb`

---

## Notebook 3 — Spam Detection with LSTM Networks

### Overview

This notebook presents an end-to-end NLP project for SMS spam detection using Long Short-Term Memory (LSTM) networks. It covers text preprocessing, tokenization, TorchText pipelines, batching strategies, recurrent neural network training, and evaluation on a real-world text classification task.

### Topics Covered

- SMS spam detection
- Long Short-Term Memory (LSTM)
- Text preprocessing
- TorchText
- Word embeddings
- Sequence classification
- Transfer learning concepts
- Deep learning with PyTorch

### Notebook

`notebooks/03_spam_detection_lstm.ipynb`

---

# 🎯 Learning Objectives

Throughout this repository, I explore how to:

- Build recurrent neural networks for NLP tasks.
- Process and batch variable-length text sequences.
- Learn distributed word representations using embeddings.
- Generate text using character-level recurrent neural networks.
- Train LSTM models for text classification.
- Develop complete NLP workflows using PyTorch.

---

# 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/Miladsaeedi70/natural-language-processing-pytorch.git
```

Navigate to the project:

```bash
cd natural-language-processing-pytorch
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebooks in numerical order:

1. Recurrent Neural Networks
2. Generative RNNs
3. Spam Detection with LSTM

---

# ⭐ About

This repository showcases practical Natural Language Processing projects implemented with PyTorch. Beginning with recurrent neural networks for text classification, it progresses to generative language modeling and concludes with a complete LSTM-based spam detection project. The notebooks have been reorganized and modernized to improve readability, reproducibility, and compatibility with recent versions of PyTorch and Python.

---

# 📄 License

This repository is intended for educational and portfolio purposes.
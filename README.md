# LLMs From Scratch

**Understanding and building Large Language Models from the ground up.**

This repository is my hands-on journey into understanding how Large Language Models (LLMs) actually work — from fundamental concepts to implementing Transformer architectures, training language models, and experimenting with fine-tuning.

Instead of treating LLMs as black boxes or simply learning how to call APIs, the goal is to understand their internal mechanisms and build things from first principles.

## 🎯 Objectives

- Understand how Large Language Models work internally.
- Implement core deep learning concepts using Python and PyTorch.
- Understand tokenization, embeddings, and positional encoding.
- Build Transformer architectures from scratch.
- Understand self-attention and multi-head attention.
- Train a small language model on custom datasets.
- Explore pretraining and fine-tuning.
- Experiment with inference, generation, and optimization.
- Develop a strong foundation for building production-grade AI systems.

## 📋 Prerequisites

Before diving into building Large Language Models, it's helpful to have a basic understanding of the following:

- [x] Python for Deep Learning
- [x] NumPy fundamentals
- [x] PyTorch fundamentals
- [x] Tensors, Autograd, and Neural Networks
- [x] Training Loops and Optimization

These prerequisites provide the programming and mathematical foundations needed to understand and implement LLM architectures.

## 📚 Learning Roadmap

### 1. Tokenization & Dataset Preparation
- [x] Understanding tokenization
- [x] Byte Pair Encoding (BPE)
- [x] Token IDs and vocabulary
- [x] Creating input-target pairs
- [x] Building custom PyTorch Datasets
- [x] Batching data using DataLoader
- [x] Implementing a tokenizer from scratch

### 2. Understanding Transformers
- [ ] Token embeddings
- [ ] Positional embeddings
- [ ] Self-attention
- [ ] Causal attention
- [ ] Multi-head attention
- [ ] Feed-forward networks
- [ ] Layer normalization
- [ ] Residual connections
- [ ] Transformer architecture

### 3. Building an LLM
- [ ] Implement a tokenizer
- [ ] Build a GPT-style Transformer
- [ ] Implement the training pipeline
- [ ] Train a small language model
- [ ] Implement text generation
- [ ] Experiment with sampling strategies

### 4. Pretraining & Fine-Tuning
- [ ] Understand pretraining objectives
- [ ] Prepare custom datasets
- [ ] Pretrain a small language model
- [ ] Fine-tune a pretrained model
- [ ] Explore instruction fine-tuning
- [ ] Evaluate model performance

### 5. Beyond the Fundamentals
- [ ] Understand inference optimization
- [ ] Explore quantization
- [ ] Explore LoRA and QLoRA
- [ ] Experiment with model evaluation
- [ ] Explore efficient LLM training techniques

## 🧪 Notebooks & Implementations

A collection of practical notebooks covering LLM fundamentals and implementations.

| # | Topic | Description |
|---|---|---|
| 01 | Input-Target Pairs & DataLoader | Tokenizing text, preparing next-token prediction datasets, and batching with PyTorch DataLoader |

More notebooks will be added as the project progresses.

## 🛠️ Tech Stack

- **Language:** Python
- **Deep Learning:** PyTorch
- **Numerical Computing:** NumPy
- **Models & Datasets:** Hugging Face
- **Development:** Jupyter Notebook / VS Code
## 📖 Primary Learning Resource

This repository follows the concepts, learning sequence, and practical implementations from:

**[Build a Large Language Model (From Scratch)](https://www.manning.com/books/build-a-large-language-model-from-scratch)**

**Author:** Sebastian Raschka

The book serves as the primary reference for understanding LLM internals and implementing a GPT-style language model from scratch using PyTorch.

Additional resources may be used to strengthen specific concepts and explore topics beyond the book.

### Learning Approach

- Follow the book chapter by chapter.
- Implement concepts through hands-on Jupyter notebooks.
- Experiment with the implementations rather than simply reproducing them.
- Document important concepts, observations, and experiments.
- Gradually progress toward building and training language models independently.

  
## 💡 Philosophy

- **Understand, don't just use:** Focus on understanding the internals rather than relying entirely on abstractions.
- **Build, don't just watch:** Every major concept should lead to a practical implementation.
- **Experiment and iterate:** Learn by testing ideas, analyzing results, and improving implementations.
- **Document the journey:** Keep track of discoveries, mistakes, experiments, and lessons learned.

## 📖 Learning Resources

- [Build a Large Language Model (From Scratch) — Sebastian Raschka](https://github.com/rasbt/LLMs-from-scratch)
- [Hugging Face LLM Course](https://huggingface.co/learn/llm-course)
- [PyTorch Tutorials](https://pytorch.org/tutorials/)
- [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)

## 🚧 Status

**Work in Progress**

This repository will evolve as I learn, experiment, and implement different components of modern Large Language Models.

---

*Learning the internals. Building from first principles. Understanding intelligence through code.*

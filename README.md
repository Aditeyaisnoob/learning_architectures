# 📚 Neural Network Architectures: ResNet-18, GoogleNet, Transformer Encoder

This repository provides interactive visualizations and insights into three foundational deep learning architectures:

- **ResNet-18**
- **GoogleNet (Inception v1)**
- **Transformer Encoder**

These models are core components in the field of computer vision and natural language processing, and are implemented and explained in detail in the open-source book **[Dive into Deep Learning](https://d2l.ai)**.


### 🔹 1. ResNet-18 (`resnet-18.html`)

ResNet (Residual Network) is known for introducing *residual connections*, which help mitigate the vanishing gradient problem in deep neural networks.

- **Key Features:**
  - Residual blocks with identity shortcuts
  - 18 layers deep
  - Simplifies training of deeper networks

- **Use Cases:** Image classification, object detection

---

### 🔹 2. GoogleNet / Inception v1 (`google_net.html`)

GoogleNet uses an *Inception module* that applies multiple convolutions in parallel to extract multi-scale features.

- **Key Features:**
  - 22 layers deep
  - Inception blocks (1x1, 3x3, 5x5 convolutions + pooling)
  - Efficient use of computation

- **Use Cases:** Efficient image classification with high accuracy

---

### 🔹 3. Transformer Encoder (`encoder_transformer.html`)

The Transformer Encoder is a core building block of models like BERT and GPT, designed to process sequences without recurrence using *self-attention* mechanisms.

- **Key Features:**
  - Multi-head self-attention
  - Positional encodings
  - Layer normalization and residual connections

- **Use Cases:** Natural language processing tasks such as machine translation, summarization, question answering

---



## 📖 Reference

These implementations and diagrams are taken from the book:

> Aston Zhang, Zachary C. Lipton, Mu Li, and Alexander J. Smola. **[Dive into Deep Learning](https://d2l.ai/)**. (2021). An interactive deep learning book with code, math, and discussions.

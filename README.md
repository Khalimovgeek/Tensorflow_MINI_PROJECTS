# ICFOSS Machine Learning & NLP Notebooks

This repository contains a comprehensive suite of machine learning, deep learning, and natural language processing (NLP) mini-projects developed during my tenure as a Machine Learning Intern at ICFOSS. Each project focuses on solving a distinct problem, ranging from computer vision classification to sequence modeling and intent tagging.

All source code, experimental pipelines, and training workflows are preserved in version-controlled Jupyter Notebooks.

---

## 🚀 Repository Structure & Projects

### 👁️ Computer Vision

#### 1. 3-Class Fruit Image Classifier
* **Objective:** Build a robust image classifier capable of distinguishing between bananas, apples, and oranges.
* **Tech Stack:** Python, TensorFlow, Keras, NumPy, Matplotlib.
* **Key Implementation:** Handled data augmentation to prevent overfitting, image resizing pipelines, and custom categorical cross-entropy loss optimization.

#### 2. Custom CNN on CIFAR-10
* **Objective:** Design, train, and evaluate a custom Convolutional Neural Network (CNN) architecture from scratch on the baseline CIFAR-10 dataset.
* **Tech Stack:** TensorFlow, Keras, NumPy.
* **Key Implementation:** Implemented alternating Convolutional and Max-Pooling layers, Dropout for regularization, and Batch Normalization to stabilize training metrics. Benchmarked final test accuracy against standard baseline metrics.

#### 3. Transfer Learning with ResNet18 / MobileNetV2
* **Objective:** Leverage deep pre-trained weights to classify custom target images, evaluating the efficiency trade-offs between dense and lightweight architectures.
* **Tech Stack:** TensorFlow/Keras (or PyTorch), ResNet18, MobileNetV2.
* **Key Implementation:** Feature extraction using frozen base layers, fine-tuning of the top dense layers, and comparison of model accuracy vs. inference speed.

---

### 📝 Natural Language Processing (NLP)

#### 4. News Category Classifier
* **Objective:** Classify short text snippets and news articles into structured thematic domains (e.g., Sports, Tech, Politics).
* **Tech Stack:** Python, Scikit-learn (or TensorFlow), NLTK/SpaCy, Pandas.
* **Key Implementation:** Text preprocessing (tokenization, stop-word removal, lemmatization) followed by vectorization (TF-IDF / Text Embeddings) and supervised classification.

#### 5. Named Entity Recognition (NER) Pipeline
* **Objective:** Deconstruct sentences to extract and tag real-world entities like names, dates, and organizations.
* **Tech Stack:** TensorFlow, Keras, NumPy.
* **Key Implementation:** Implemented a sequence-to-sequence **BiLSTM + CRF (Bidirectional LSTM with Conditional Random Fields)** architecture to effectively map contextual token transitions.

#### 6. Question Classifier (Intent Tagging)
* **Objective:** Analyze and tag inquiries based on their core analytical intent type (e.g., *What, Who, Why, Where*).
* **Tech Stack:** Python, NLP Sequence Processing, TensorFlow.
* **Key Implementation:** Developed text token embedding mapping, which serves as a core foundational component for routing queries within conversational AI and Retrieval-Augmented Generation (RAG) architectures.

---

## 🛠️ Core Mathematical & Practical Foundations
Beyond raw framework modeling, these notebooks implement and rely heavily on core machine learning math principles for feature calculations and evaluations:
* **Linear Algebra Applications:** High-dimensional vector multiplications and dot products for processing text and image feature maps.
* **Metric Calculations:** Manual and framework-level implementations of **Cosine Similarity** to gauge feature vector alignment and text embedding comparisons.

---

## ⚙️ Setup and Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/khalimovgeek/your-repo-name.git](https://github.com/khalimovgeek/your-repo-name.git)
   cd your-repo-name

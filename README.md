# ToxiScan- Multi-Label Toxic Comment Detection

ToxiScan is an end-to-end NLP system for detecting multiple forms of toxicity in online comments, such as toxic, obscene, threat, insult, and identity-based hate.  
The project is built using a Bi-directional LSTM model trained on the Jigsaw Toxic Comment dataset and supports real-time inference through a Gradio interface.

---

## Key Features

- Multi-label toxic comment classification
- Text preprocessing using TensorFlow TextVectorization
- Efficient `tf.data` pipeline for training
- Bi-directional LSTM with learned word embeddings
- Model evaluation using precision, recall, and accuracy
- Interactive Gradio-based inference interface

---

## Model Overview

- Architecture: Embedding → BiLSTM → Dense layers → Sigmoid outputs  
- Loss Function: Binary Crossentropy  
- Optimizer: Adam  
- Output: Independent probabilities for each toxicity category

---

## Dataset

This project uses the **Jigsaw Toxic Comment Classification Challenge** dataset.

Dataset source:  
https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge


---


## Tech Stack

Python, TensorFlow, Keras, NLP, BiLSTM, Gradio

---

## Author

**Vyom Chaturvedi**  
CSE undergrad

#  Image Captioning with Attention Mechanism

This project implements an end-to-end **image captioning model** using **Convolutional Neural Networks (CNNs)** for image feature extraction and **Recurrent Neural Networks (LSTMs)** for generating natural language captions. An **attention mechanism** is integrated to improve focus on relevant image regions while generating each word.

---

##  Project Highlights

- **Dataset:** [Flickr8k](https://www.kaggle.com/datasets/adityajn105/flickr8k)
- **Framework:** TensorFlow, Keras
- **Architecture:**
  - **CNN Encoder:** Pretrained ResNet50
  - **RNN Decoder:** LSTM with Bahdanau-style attention
- **Training Strategy:** Teacher forcing, padding, and early stopping
- **Evaluation:** BLEU scores and qualitative caption outputs
- **Notebook:** Developed in Google Colab
- **Output:** Image with auto-generated captions

---

##  Architecture Overview

Image (Flickr8k) → CNN Encoder → Feature Vector
↓
Attention Mechanism
↓
LSTM Decoder → Word-by-word Caption

## Evaluation Metrics
- BLEU-1, BLEU-2, BLEU-3, BLEU-4 scores
- Qualitative caption outputs on unseen images

##  Key Features
- Encoder-Decoder with Bahdanau Attention
- Pretrained CNN for rich image features
- Sequence modeling with LSTM decoder
- Uses Teacher Forcing during training
- Tested and visualized using Colab Notebook

## Results
- Generated semantically relevant captions on test images
- Improved accuracy and focus with attention mechanism
- Achieved BLEU-1 score of 0.52 and BLEU-4 score of 0.088 on Flickr8k, indicating reasonable word-level caption accuracy using attention-enhanced CNN-LSTM architecture.


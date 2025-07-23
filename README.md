# Signature-Verification-
We are implementing here a Python code to verify and filter the genuine and forgery signature.
Here is a short and clear `README.md` content for your **Signature Verification Using CNN** project:

---

# Signature Verification Using CNN

This project implements an offline signature verification system using **Convolutional Neural Networks (CNNs)**. It classifies signatures as *genuine* or *forged* by analyzing visual features from scanned signature images.

## 🧠 Overview

* **Goal**: Enhance security and identity verification using machine learning.
* **Method**: Use CNNs for automated feature extraction and binary classification.
* **Data**: Combined dataset of genuine and forged signatures (self-collected + Kaggle).

## 📊 Features

* Custom CNN architecture built with Keras.
* Data preprocessing and augmentation (resizing, normalization, flipping, etc.).
* Trained on labeled signature images.
* Evaluated using accuracy, loss, confusion matrix, precision, recall, and F1-score.

## 📁 Project Structure

* `dataset/`: Contains organized signature images.
* `model.py`: Defines the CNN architecture.
* `train.py`: Training and evaluation scripts.
* `utils.py`: Preprocessing and helper functions.
* `results/`: Accuracy graphs, confusion matrices, and model checkpoints.

## 🔧 Technologies

* Python
* Keras / TensorFlow
* OpenCV
* NumPy / Matplotlib / scikit-learn

## 📈 Results

| Epochs | Accuracy |
| ------ | -------- |
| 100    | 92.0%    |
| 500    | 94.7%    |

## 📌 Future Work

* Explore advanced architectures like VGG, ResNet, Inception.
* Develop a web-based interface for real-time verification.
* Expand dataset and apply in real-world use cases.

---



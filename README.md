# 🌸 Oxford Flowers 102 - Image Classification with CNN and EfficientNetB0

This project implements an end-to-end image classification model using the **Oxford Flowers 102** dataset. It begins with a **Convolutional Neural Network (CNN)** built from scratch, then transitions to using **EfficientNetB0**, the baseline model from *"Rethinking Model Scaling for Convolutional Neural Networks."*

The workflow includes **data preprocessing**, **advanced data augmentation**, **regularization**, and performance evaluation with the goal of minimizing overfitting and maximizing classification accuracy.

---

## 🧠 Key Features

- 📦 **Dataset**: [Oxford 102 Flower Categories](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/)
- 🧱 **Model 1**: Custom CNN (built from scratch)
- ⚡ **Model 2**: EfficientNetB0 (pre-trained on ImageNet, fine-tuned on Flowers102)
- 🔄 **Augmentation**: RandomFlip, Rotation, Zoom, Contrast, etc.
- 🛡️ **Regularization**: Dropout, EarlyStopping, L2 Weight Decay
- 📊 **Metrics**: Accuracy, Loss curves, Confusion Matrix, Top-5 Accuracy

---

## 🛠️ Tech Stack

- Python 3.x
- TensorFlow / Keras
- NumPy, Matplotlib, seaborn
- `tensorflow_hub`, `tensorflow_datasets`

---

## 📁 Project Structure

# 🐶 Cat vs Dog Image Classification using CNN

This project is an image classification model built using **Convolutional Neural Networks (CNNs)** to classify images as either **cats** or **dogs**. It is implemented using **TensorFlow/Keras** and trained in **Google Colab** on the [Dogs vs Cats dataset](https://www.kaggle.com/datasets/salader/dogs-vs-cats) from Kaggle.

---

## 📁 Dataset

- **Source**: [Kaggle - Dogs vs Cats](https://www.kaggle.com/datasets/salader/dogs-vs-cats)
- Includes labeled images of cats and dogs.
- Training and test sets are prepared using TensorFlow's `image_dataset_from_directory`.

---

## 🧠 Model Architecture

- 3 × Conv2D + BatchNormalization + MaxPooling layers
- Flatten layer
- Dense layers with Dropout
- Output: Sigmoid activation for binary classification

---

## 🔧 Technologies Used

- Python 3
- TensorFlow & Keras
- OpenCV
- Matplotlib
- Google Colab

---

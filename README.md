# Neural Networks with CIFAR-10

This project demonstrates training a convolutional neural network (CNN) on the CIFAR-10 dataset using TensorFlow and Keras. The goal is to classify images into 10 different categories with good accuracy.

---

## Project Overview

- **Dataset:** CIFAR-10 (60,000 32x32 color images in 10 classes)
- **Model:** Sequential CNN with Conv2D, MaxPooling, Dense layers, and Dropout
- **Normalization:** Pixel values scaled to [0, 1]
- **Training:** Model trained for multiple epochs with validation split
- **Evaluation:** Accuracy and loss metrics tracked and plotted

---

## Requirements

- Python 3.8
- TensorFlow
- NumPy
- Matplotlib

You can install the dependencies with:

```bash
pip install tensorflow numpy matplotlib

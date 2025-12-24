# MNIST Handwritten Digit Recognition (CNN)

This project features a Deep Learning model built with a **Convolutional Neural Network (CNN)** to recognize handwritten digits (0-9) using the famous **MNIST** dataset. The model is enhanced with data augmentation techniques to improve robustness and generalization.

## 🚀 Project Overview
* **Author:** OrkhanIW (Leeks864)
* **Framework:** TensorFlow / Keras
* **Dataset:** MNIST (60,000 training samples, 10,000 test samples)
* **Preprocessing:** Data normalized to [0, 1] range and reshaped to (28, 28, 1).
* **Data Augmentation:** Used `ImageDataGenerator` for random rotations, width/height shifts, and zooms to prevent overfitting.

## 🧠 Model Architecture
The model uses a `Sequential` structure:
1. **Conv2D:** 32 filters, 3x3 kernel, ReLU activation.
2. **MaxPooling2D:** 2x2 pooling.
3. **Conv2D:** 64 filters, 3x3 kernel, ReLU activation.
4. **MaxPooling2D:** 2x2 pooling.
5. **Flatten:** Converts 2D feature maps into a 1D vector.
6. **Dense:** 128 neurons, ReLU activation.
7. **Output:** 10 neurons (one for each digit), Softmax activation.

## 📈 Performance & Results
The model was trained for 10 epochs and achieved the following performance on the test set:
* **Test Accuracy:** 99.17%
* **Test Loss:** 0.0228

## 🛠️ Installation & Usage
To run this project locally:

1. Clone the repository:
   ```bash
   git clone [https://github.com/Leeks864/OrkhanIW1.git](https://github.com/Leeks864/OrkhanIW1.git)

# 🧠 Fashion MNIST Classifier with TensorFlow & Keras

This project is a beginner-friendly implementation of a neural network that classifies clothing images from the [Fashion MNIST dataset](https://github.com/zalandoresearch/fashion-mnist). Built using TensorFlow and Keras, this project demonstrates the fundamentals of deep learning, including model design, training, evaluation, and prediction.

> 📌 **Author:** Sudharsan T  
> 🔗 [Connect on LinkedIn](https://www.linkedin.com/in/sudharsan-thirumalai-85361b1a4/)  
> 🗓️ Built: February 2025  
> 📁 Dataset: Fashion MNIST (60,000 training + 10,000 validation images)

---

## 📸 Project Demo

![fashion mnist sample](https://raw.githubusercontent.com/zalandoresearch/fashion-mnist/master/doc/img/fashion-mnist-sprite.png)

---

## 🚀 What I Built

- A neural network using **TensorFlow and Keras**.
- Trained on 60,000 grayscale 28x28 images of clothing.
- Evaluated on a separate 10,000 validation set.
- Visualized predictions to understand model confidence.
- Compared raw logits vs softmax outputs.

---

## 🧠 What I Learned

- The structure and logic of **feedforward neural networks**.
- How to load, visualize, and pre-process image datasets.
- Concepts like **loss functions**, **activation functions**, **accuracy metrics**, and **model training loops**.
- Understanding model outputs: logits, probabilities, and predictions.
- How to write and run deep learning models with **Keras Sequential API**.

---

## 🛠️ Tech Stack

| Tool / Library | Purpose |
|----------------|---------|
| Python         | Programming language |
| TensorFlow 2.x | Deep Learning framework |
| Keras API      | High-level model API |
| NumPy & Matplotlib | Data handling and visualization |
| Fashion MNIST | Clothing dataset (10 classes) |

---

## 🧬 Model Architecture

```python
model = tf.keras.Sequential([
    tf.keras.layers.Flatten(input_shape=(28, 28)),
    tf.keras.layers.Dense(10)  # Output layer: 10 neurons (one per class)
])

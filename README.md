# 🐱‍👤 Pokémon Image Classification using Custom Neural Network

This project implements an image classification model that classifies Pokémon images from Generation One using a completely custom neural network built only with **NumPy**, without using any deep learning libraries such as Keras, TensorFlow, or PyTorch.

---

## 📄 Dataset

- **Source**: [Pokémon Generation One Dataset on Kaggle](https://www.kaggle.com/datasets/thedagger/pokemon-generation-one)
- The dataset includes images of first-generation Pokémon (e.g., Pikachu, Bulbasaur, Meowth).

---

## 💡 Approach

- Images are loaded and preprocessed using **OpenCV** (resized, normalized, flattened).
- A custom fully connected neural network (multilayer perceptron) is implemented from scratch using NumPy.
- The network supports forward propagation, backpropagation, and weight updates without using any external machine learning frameworks.
- Softmax output with cross-entropy loss is used for multiclass classification.

---

## 🚀 Features

- Custom 3-layer neural network with adjustable hidden layers
- Only NumPy used for all matrix computations
- Manual implementation of forward and backward propagation
- Training loss plotted using Matplotlib
- Visualization of misclassified Pokémon images

---

## 📈 Results

The model learns to classify Pokémon images with decreasing loss across epochs, demonstrating that even a simple custom neural network can effectively separate classes with small datasets.

---

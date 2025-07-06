# 🧠 Neural Network Classifier

This project implements a feedforward neural network for binary classification using TensorFlow/Keras. It's designed to be simple, educational, and easily extendable.

---


## 📊 Dataset Overview

- **Source:** Indian Liver Patient Dataset (UCI Repository)  
- **Samples:** 583 patient records  
- **Attributes:** 10 features + target label  
- **Target:**  
  - `1` = liver disease  
  - `2` = no liver disease  

---

## 📐 Model Architecture

- **Input Layer:** 10 neurons, ReLU activation  
- **Hidden Layer:** 8 neurons, ReLU activation  
- **Output Layer:** 2 neurons, Sigmoid activation

---

## ⚙️ Training Configuration

- **Loss Function:** Binary Cross-Entropy  
- **Optimizer:** Adam  
- **Epochs:** 100  
- **Validation Split:** 20%  
- **Batch Size:** Keras default (can be customized)

---

## 🗂️ Project Structure


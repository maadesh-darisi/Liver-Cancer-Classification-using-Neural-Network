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

## 📈 Results

| Metric      | Value    |
|-------------|----------|
| Error Rate  | 0.286449 |
| Accuracy    | 0.713551 |
| Loss        | 0.535297 |
| Sensitivity | 0.293413 |
| Specificity | 0.882212 |
| Precision   | 0.500000 |
| FPR         | 0.117788 |
| MCC         | 0.212328 |
| F-score     | 0.369811 |

---

## 🔧 Workflow

### Data Preprocessing
- Fill missing values in dataset  
- Encode categorical features (e.g., Gender)  
- Normalize features and split dataset into training and validation sets  

### Model Training
- Build model using Keras Sequential API with dense layers  
- Train neural network for binary classification  
- Use binary cross-entropy loss and Adam optimizer  
- Train for 100 epochs with 20% validation split  

### Model Evaluation
- Evaluate using accuracy, precision, recall, F1-score  
- Visualize results using confusion matrix  

---
## 💡 Future Enhancements

- Explore CNN or RNN architectures for improved feature extraction  
- Implement ensemble methods (e.g., Random Forest, Gradient Boosting) for better performance  
- Hyperparameter tuning and cross-validation for model optimization  
- Deploy as a web application or API for real-time predictions  

---
## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Deep Learning Framework:** TensorFlow / Keras  
- **Data Manipulation:** NumPy, Pandas  
- **Data Preprocessing & Evaluation:** Scikit-learn  
- **Visualization:** Matplotlib, Seaborn (for confusion matrix and metrics plots)  
- **Development Environment:** Jupyter Notebook / VS Code / Any Python IDE  


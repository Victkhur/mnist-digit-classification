# 🧠 MNIST Handwritten Digit Classification  
This project builds a **Deep Learning model** to classify handwritten digits (0-9) using the **MNIST dataset**.  
It includes **Batch Normalization, Dropout, and Hyperparameter Tuning** to improve accuracy.  

---

## 📌 Project Overview  
MNIST is a dataset of **28x28 grayscale images** of handwritten digits (0-9).  
The goal is to train a neural network to accurately classify these digits.  

🔹 **Dataset:** [MNIST Handwritten Digits](http://yann.lecun.com/exdb/mnist/)  
🔹 **Libraries Used:** `TensorFlow`, `Keras`, `Matplotlib`, `NumPy`  
🔹 **Techniques Implemented:**  
   ✅ Fully Connected Neural Network (MLP)  
   ✅ Batch Normalization & Dropout (Prevent Overfitting)  
   ✅ Hyperparameter Tuning (Keras Tuner)  
   ✅ Model Evaluation (Accuracy & Loss Plots)  

---

## 🚀 Features  
✔ **98.03% Test Accuracy** on MNIST dataset  
✔ **Batch Normalization & Dropout** for better generalization  
✔ **Hyperparameter Optimization** using Keras Tuner  
✔ **Visualized Accuracy & Loss Graphs**  

---

## 📂 Project Structure  
```bash
mnist-digit-classification/
│── notebooks/                  # Jupyter notebooks (if applicable)
│── results/                     # Accuracy reports & loss curves
│── mnist_classification.py      # Main Python script
│── hyperparameter_tuning.py     # Keras Tuner script for optimization
│── requirements.txt             # Dependencies
│── README.md                    # Project documentation
```

## ⚡ Model Architecture
The model consists of:

✔ Flatten Layer – Converts 2D images into 1D vectors

✔ Dense Layers – Fully connected layers for learning patterns

✔ Batch Normalization – Normalizes activations to stabilize training
✔ Dropout – Reduces overfitting
✔ Softmax Layer – Outputs probabilities for 10 classes (digits 0-9)

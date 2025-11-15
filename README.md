# Deep-learning-Assignment
Implementation of CNN and a Recurrent Neural Network models
Author: Anushree D.  
Course: Deep Learning  
---

## 📌 Overview  
This repository contains **three deep learning experiments** implemented using **TensorFlow / Keras**:

1. **CNN on CIFAR-10** – Basic Convolutional Neural Network  
2. **CNN Transfer Learning on Flowers Dataset** – EfficientNetB0  
3. **RNN using LSTM on IMDb Reviews** – Sentiment Analysis  

Each experiment is implemented in a separate `.ipynb` notebook and includes:  
✔ Dataset loading  
✔ Model building  
✔ Training  
✔ Evaluation  
✔ Saving results  

---

# 1️⃣ CNN on CIFAR-10  
**File:** `CNN_CIFAR10.ipynb`

### 📘 Description  
A simple CNN built from scratch to classify 10 categories in the CIFAR-10 image dataset (airplane, car, bird, cat, etc.).

### 🧠 Key Steps  
- Load CIFAR-10 dataset using `tf.keras.datasets`  
- Normalize pixel values  
- Build a CNN using Conv2D, MaxPooling, Flatten, Dense  
- Train for multiple epochs  
- Plot training accuracy and loss  
- Save model & graphs

### 📂 Dataset  
CIFAR-10 (built-in TensorFlow dataset)

---

# 2️⃣ CNN Transfer Learning on Flowers  
**File:** `CNN_FLOWERS_TRANSFER.ipynb`

### 📘 Description  
Transfer learning using **EfficientNetB0** pretrained on ImageNet, applied to the **TensorFlow Flowers dataset** (5 categories).

### 🧠 Key Steps  
- Load dataset using TensorFlow Datasets (`tfds`)  
- Resize images to 224×224  
- Freeze base EfficientNet layers  
- Add custom classification head  
- Train head  
- Fine-tune deeper layers (optional)  
- Plot and save accuracy graphs  
- Export trained model

### 📂 Dataset  
TensorFlow Flowers Dataset (5 classes)  
Loaded using `tfds.load('tf_flowers', ...)`

---

# 3️⃣ RNN with LSTM on IMDb Sentiment Analysis  
**File:** `RNN_IMDB_LSTM.ipynb`

### 📘 Description  
A simple RNN model using LSTM to classify IMDb movie reviews into **positive** or **negative** sentiment.

### 🧠 Key Steps  
- Load IMDb dataset using Keras  
- Preprocess sequences and pad them  
- Build model (Embedding → LSTM → Dense)  
- Train model  
- View accuracy and summary  

### 📂 Dataset  
IMDb Reviews (built-in TensorFlow dataset)

---

# 📁 Folder Structure  


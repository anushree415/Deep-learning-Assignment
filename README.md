# Deep-learning-Assignment
Implementation of CNN and a Recurrent Neural Network models
Author: Anushree D.  
Course: Deep Learning  

---

## 📌 Overview  
This repository contains three deep learning experiments implemented using TensorFlow/Keras:

1. **CNN on CIFAR-10**  
2. **CNN Transfer Learning on Flowers Dataset**  
3. **RNN LSTM on IMDb Sentiment Analysis**

Each notebook includes model creation, training, evaluation, and saved results.

---

# 1️⃣ CNN on CIFAR-10  
**File:** `CNN_CIFAR10.ipynb`

A simple convolutional neural network for CIFAR-10 image classification.

### 🧠 Model Summary  
- Conv2D + MaxPooling  
- Flatten + Dense layers  
- Softmax output for 10 classes  

### 📊 Accuracy Graph  
![CNN CIFAR10 Accuracy](results/cifar10_accuracy.png)

### 📉 Loss Graph  
![CNN CIFAR10 Loss](results/cifar10_loss.png)

---

# 2️⃣ CNN Transfer Learning — Flowers Dataset  
**File:** `CNN_FLOWERS_TRANSFER.ipynb`

Transfer learning using **EfficientNetB0** pretrained on ImageNet.

### 🧠 Model Steps  
- Load `tf_flowers` dataset  
- Resize to `224×224`  
- Freeze EfficientNet base  
- Add custom dense layers  
- Fine-tune deeper layers  

### 📊 Transfer Learning Accuracy  
![Flowers Transfer Accuracy](results/flowers_transfer_accuracy.png)

### 🌸 Sample Images from Dataset  
![Flowers Samples](results/flowers_samples.png)

> *(If you didn’t save sample images, you may remove the above line.)*

---

# 3️⃣ RNN with LSTM — IMDb Sentiment Analysis  
**File:** `RNN_IMDB_LSTM.ipynb`

Sentiment classification using **Embedding → LSTM → Dense** architecture.

### 📊 Training Accuracy  
![LSTM Accuracy](results/lstm_accuracy.png)

### 📉 Training Loss  
![LSTM Loss](results/lstm_loss.png)

---

# 📂 Project Structure  

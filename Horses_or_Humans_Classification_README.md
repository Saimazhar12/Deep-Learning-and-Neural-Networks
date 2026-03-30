# 🐴👤 Horses vs Humans Image Classification using CNN

This project implements a deep learning-based image classification system to distinguish between **horses and humans** using a Convolutional Neural Network (CNN). The model is trained on an image dataset and is capable of accurately classifying unseen images.

## 📌 Project Overview
The goal of this project is to build a **binary classifier** that identifies whether an image belongs to a **horse 🐴** or **human 👤** category. CNN is used to automatically learn important visual features such as shapes, textures, and patterns from the images.

## 📂 Dataset
- Dataset: Horses vs Humans Dataset  
- Image Type: RGB Images  
- Image Size: 224 × 224  
- Classes:  
  - Horse 🐴  
  - Human 👤  

## ⚙️ Features
- CNN-based architecture  
- Image preprocessing and normalization  
- Data augmentation (rotation, flipping, etc.)  
- Binary classification  
- Early stopping and model checkpointing  
- Performance visualization  

## 🧠 Model & Training
- Optimizer: Adam  
- Loss Function: Binary Crossentropy  
- Batch Size: 32  
- Epochs: 30  
- Input Shape: (224, 224, 3)  

## 📊 Results
The model achieves strong accuracy on validation data and shows good performance in distinguishing between horses and humans. It generalizes well to unseen images.

## 🛠️ Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Scikit-learn  

## 🚀 How to Run
1. Clone the repository  
2. Install dependencies  
3. Open the Google Colab  
4. Run all cells step by step  

## 📌 Conclusion
This project demonstrates the effectiveness of CNNs for **binary image classification tasks**. The model performance can be further improved using **transfer learning (ResNet50, VGG16, InceptionV3)** and hyperparameter tuning.

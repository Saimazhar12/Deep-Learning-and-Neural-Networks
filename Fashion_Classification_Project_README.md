# 👕 Fashion Image Classification using CNN

This project implements a deep learning-based image classification system to classify different types of fashion items using a Convolutional Neural Network (CNN). The model is trained on the Fashion MNIST dataset and is capable of accurately classifying unseen images.

## 📌 Project Overview
The goal of this project is to build a multi-class classifier that identifies different categories of clothing items. CNN is used to automatically learn important visual patterns and features from grayscale images.

## 📂 Dataset
- Training Images: 60,000  
- Testing Images: 10,000  
- Image Size: 28 × 28 (grayscale)  
- Classes:
  - T-shirt/top 👕  
  - Trouser 👖  
  - Pullover 🧥  
  - Dress 👗  
  - Coat 🧥  
  - Sandal 👡  
  - Shirt 👔  
  - Sneaker 👟  
  - Bag 👜  
  - Ankle boot 👢  

## ⚙️ Features
- CNN-based architecture  
- Data preprocessing and normalization  
- Multi-class classification  
- Model evaluation using accuracy and confusion matrix  
- Visualization of predictions  

## 🧠 Model & Training
- Optimizer: Adam  
- Loss Function: Sparse Categorical Crossentropy  
- Batch Size: 512  
- Epochs: 10  

## 📊 Results
The model achieves good accuracy on unseen test data, demonstrating strong performance in classifying different fashion categories.

## 🛠️ Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

## 🚀 How to Run
1. Clone the repository  
2. Install dependencies  
3. Open the Google Colab
4. Run all cells step by step 

## 📌 Conclusion
This project highlights the effectiveness of CNNs for multi-class image classification and can be further improved using deeper networks, data augmentation, or transfer learning.

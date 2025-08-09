# MNIST-CNN-RECOGNITION

# 🔢 MNIST Handwritten Digit Recognition (CNN)

## 📌 Overview
This project implements a **Convolutional Neural Network (CNN)** to recognize and classify handwritten digits (0–9) from the **MNIST dataset**.  
The MNIST dataset contains 60,000 training images and 10,000 test images of handwritten digits in grayscale (28x28 pixels).  

# 📂 Project Structure
```
├── AFOLAYAN_IFEOLUWA_ML_INTERN _2.ipynb # Main training script
├── mnist_cnn_model.h5 # Saved trained CNN model
├── requirements.txt # Required dependencies
├── README.md # Project documentation
└── data/ # MNIST dataset (downloaded automatically)
```

## 🧠 Model Architecture
The CNN model used:
```
Conv2D layer (32 filters, 3x3 kernel, ReLU activation)
Conv2D layer (64 filters, 3x3 kernel, ReLU activation)
MaxPooling2D layer (2x2)
Dropout (5%)
Flatten
Dense layer (128 units, ReLU activation)
Dropout (50%)
```

## 🚀 Training
### accuracy: 0.9873 - loss: 0.0424 - val_accuracy: 0.9913 - val_loss: 0.0259

## 📊 Model Performance
```
Test loss: 0.025917034596204758
Test accuracy: 0.9912999868392944
Test Accuracy: 99.13%
```
### Test Accuracy: 99.13%

Dense output layer (10 units, Softmax activation)

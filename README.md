# 🖼️ Image Classification using CNNs

A deep **Convolutional Neural Network (CNN)** model for **multi-class image classification** achieving **94% accuracy** on the **CIFAR-10 dataset** with **data augmentation** techniques to enhance generalization and prevent overfitting.

---

## 📌 Project Overview
This project uses a **custom CNN architecture** built with **TensorFlow/Keras** for classifying images from the CIFAR-10 dataset into 10 categories, including airplanes, automobiles, birds, cats, deer, dogs, frogs, horses, ships, and trucks.  
Data augmentation techniques such as **rotation, flipping, and shifting** are applied to improve model performance.

---

## 🚀 Features
- **Deep CNN architecture** with convolution, pooling, batch normalization, and dropout layers  
- **Data Augmentation** for better generalization  
- Achieves **94% test accuracy** on CIFAR-10  
- **OpenCV preprocessing** integration  
- Accuracy/Loss **visualization plots**  
- **Sample predictions** with color-coded correctness  

---

## 🛠 Tech Stack
- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **Matplotlib**
- **NumPy / Pandas**

---

## 📂 Dataset
The CIFAR-10 dataset is automatically downloaded via Keras:
```python
from tensorflow.keras import datasets
(x_train, y_train), (x_test, y_test) = datasets.cifar10.load_data()

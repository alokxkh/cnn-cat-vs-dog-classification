#  Cat vs Dog Image Classification using CNN

##  Project Overview

This project implements a **Convolutional Neural Network (CNN)** to classify images as **cats** or **dogs** using TensorFlow and Deep Learning techniques.

The model learns visual features such as edges, textures, and shapes to accurately distinguish between the two classes.

---

##  Objectives

* Build a CNN model for binary image classification
* Classify images into **Cat** or **Dog**
* Apply data preprocessing and augmentation
* Evaluate model performance

---

##  Technologies Used

* Python 
* TensorFlow / Keras
* TensorFlow Datasets
* Google Colab
* Deep Learning (CNN)

---

##  Dataset

Dataset used: **Cats vs Dogs** from TensorFlow Datasets.

It contains thousands of labeled images of cats and dogs for training and validation.

---

##  Model Architecture

The CNN model includes:

* Convolutional Layers
* Batch Normalization
* MaxPooling Layers
* Dropout Layer
* Fully Connected Dense Layer
* Sigmoid Output Layer

---

##  How It Works

1. Load dataset using TensorFlow Datasets
2. Resize and normalize images
3. Apply data augmentation
4. Train CNN model
5. Evaluate accuracy on validation data

---

##  How to Run the Project

###  Clone the repository

```bash
git clone https://github.com/alokk2005/cnn-cat-vs-dog-classification.git
cd cnn-cat-vs-dog-classification
```

###  Install dependencies

```bash
pip install tensorflow tensorflow-datasets
```

###  Run the notebook

Open the notebook in **Google Colab** and run all cells.

---

##  Results

* Training Accuracy: ~90%
* Validation Accuracy: ~85–90%
* Model successfully distinguishes cats and dogs.

---

##  Sample Output

The model predicts:

*  Cat
*  Dog

---

##  Future Improvements

* Use Transfer Learning (VGG16, ResNet)
* Deploy as a web app
* Improve accuracy with hyperparameter tuning

---

##  Author

**Alok**
B.Tech Student | Deep Learning Enthusiast

##  Co-Authored By

**AYIKxD**
B.tech Student | Android Developer
---

##  If you like this project

Give it a  on GitHub!

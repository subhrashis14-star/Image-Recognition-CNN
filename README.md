# Image Recognition Using Convolutional Neural Networks (CNN)

## Project Overview

This project implements an Image Recognition System using a Convolutional Neural Network (CNN) built with TensorFlow and Keras. The model is trained to classify images into two categories: **Cats** and **Dogs**.

The project demonstrates the complete deep learning workflow, including dataset extraction, preprocessing, model building, training, evaluation, and image prediction.

---

## Features

* Dataset extraction from ZIP files
* Automatic dataset organization
* Image preprocessing and normalization
* CNN-based image classification
* Model training and validation
* Accuracy and loss visualization
* Single-image prediction
* Model saving for future use

---

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Google Colab

---

## Project Workflow

### 1. Dataset Upload and Extraction

The dataset is uploaded as a ZIP file and extracted into the working directory.

### 2. Dataset Preparation

Images are automatically separated into:

* Training Dataset

  * Cats
  * Dogs

* Testing Dataset

  * Cats
  * Dogs

### 3. Data Loading

Images are loaded using TensorFlow's `image_dataset_from_directory()` function.

### 4. Preprocessing

* Image resizing to 150 × 150 pixels
* Pixel normalization (0–255 → 0–1)

### 5. CNN Model Architecture

The model consists of:

* Convolutional Layers (Conv2D)
* Max Pooling Layers
* Flatten Layer
* Dense Layers
* Output Layer for Binary Classification

### 6. Model Training

* Optimizer: Adam
* Loss Function: Binary Crossentropy
* Metric: Accuracy
* Epochs: 5

### 7. Evaluation

The trained model is evaluated on the test dataset using:

* Test Accuracy
* Test Loss

### 8. Prediction

The model can classify new images as:

* Cat
* Dog

---

## Results

The model achieves image classification using a CNN architecture and provides visual performance metrics through training and validation accuracy graphs.

---

## Files

```text
Image-Recognition-CNN/
│
├── image_recognisation.ipynb
├── README.md
└── requirements.txt
```

---

## Installation

Install required libraries:

```bash
pip install tensorflow numpy matplotlib pillow scikit-learn
```

---

## How to Run

1. Clone the repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Upload the dataset ZIP file.
4. Run all notebook cells sequentially.
5. Train the CNN model.
6. Test with a custom image.

---

## Future Improvements

* Increase training epochs
* Add Data Augmentation
* Use Transfer Learning (VGG16, ResNet, EfficientNet)
* Improve model accuracy with larger datasets
* Deploy as a web application

---

## Author

**Subhrashis**

Deep Learning and Computer Vision Project using TensorFlow and Keras.

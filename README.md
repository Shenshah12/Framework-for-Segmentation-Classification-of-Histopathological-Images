# Image Segmentation and Classification

This project implements image segmentation and classification using a U-Net model and a custom classification model. The goal is to accurately segment histopathological images into different classes and classify them accordingly.

---

## 📌 Project Overview

The project consists of the following components:

### 1. Data Preparation
- Images and corresponding masks are loaded from the dataset.
- Preprocessing includes gamma correction and conversion to RGB format.
- Masks are one-hot encoded based on a predefined colormap.

### 2. U-Net Model (Segmentation)
- A U-Net architecture is used for image segmentation.
- The model learns to segment images into multiple tissue classes using annotated masks.

### 3. Custom Classification Model
- A CNN-based classification model is applied to segmented outputs.
- It classifies segmented regions into specific categories.

### 4. Evaluation
- Performance is evaluated using:
  - Accuracy Score
  - Confusion Matrix
- Metrics are used to assess both segmentation and classification results.

---

## 🚀 Usage

### Data Preparation
Run the `Prepare_Data` class to load and preprocess images and masks.  
Update image and mask paths accordingly and adjust preprocessing parameters such as gamma correction if needed.

### Model Training
- Train the U-Net model for segmentation.
- Train the custom CNN model for classification.
- Configure loss functions, optimizers, and hyperparameters as required.

### Model Evaluation
- Evaluate trained models using accuracy and confusion matrix.
- Visualize results for performance analysis.

---

## 📊 Dataset

The dataset used in this study can be collected from the University of Queensland:

https://espace.library.uq.edu.au/view/UQ:8be4bd0

---

## ⚙️ Dependencies

- Python (3.11.22)
- OpenCV (4.7.0)
- NumPy (1.23.5)
- Matplotlib (3.7.1)
- Scikit-learn (1.2.2)
- TensorFlow (2.12.0)
- Keras (2.12.0)

---

## 🧠 Models Used

- U-Net (for image segmentation)
- Custom CNN (for classification)

---

## 📌 Note
This project combines segmentation and classification to improve automated analysis of histopathological images.

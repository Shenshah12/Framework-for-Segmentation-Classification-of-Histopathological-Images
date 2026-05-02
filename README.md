# Image Segmentation and Classification

This project presents a deep learning framework for histopathological image analysis using a U-Net model for segmentation and a custom convolutional neural network (CNN) for classification. The objective is to accurately segment tissue structures and classify them into relevant diagnostic categories.

---

## 📌 Project Overview

The proposed pipeline consists of the following stages:

### 1. Data Preparation
Histopathological images and their corresponding segmentation masks are loaded from the dataset. Preprocessing steps include gamma correction, normalization, and conversion to RGB format. The masks are then encoded using a predefined colormap to generate one-hot representations for training.

### 2. Image Segmentation (U-Net)
A U-Net architecture is employed to perform pixel-level segmentation of histopathological images. The encoder–decoder structure, along with skip connections, enables precise localization of tissue regions and preserves spatial information.

### 3. Image Classification (CNN)
A custom convolutional neural network is used to classify the segmented regions into specific pathological categories. The model learns hierarchical feature representations from the segmented outputs to improve classification accuracy.

### 4. Evaluation
The performance of the framework is assessed using standard evaluation metrics, including accuracy and confusion matrix analysis. These metrics provide insight into both segmentation quality and classification performance.

---

## 🚀 Workflow

- Preprocess dataset (images + masks)
- Train U-Net model for segmentation
- Generate segmented outputs
- Train CNN classifier on segmented regions
- Evaluate using accuracy and confusion matrix

---

## 📊 Dataset

The dataset used in this study is available from the University of Queensland:

https://espace.library.uq.edu.au/view/UQ:8be4bd0

---

## 🧠 Method Summary

This framework integrates segmentation and classification into a unified pipeline, enabling improved interpretability and performance in histopathological image analysis. U-Net is used to capture fine-grained spatial details, while the CNN focuses on discriminative feature learning for classification.

---

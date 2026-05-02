# Image Segmentation and Classification

This project presents a deep learning framework for histopathological image analysis using a U-Net model for segmentation and a custom convolutional neural network (CNN) for classification. The objective is to accurately segment tissue structures and classify them into relevant diagnostic categories using ground-truth annotations.

---

## 📌 Project Overview

The proposed pipeline consists of the following stages:

### 1. Data Preparation
Histopathological images and their corresponding segmentation masks are loaded from the dataset. Preprocessing steps include gamma correction, normalization, and conversion to RGB format. The masks are encoded using a predefined colormap and transformed into one-hot representations for supervised learning.

### 2. Image Segmentation (U-Net)
A U-Net architecture is employed for pixel-level segmentation of histopathological images. Its encoder–decoder structure with skip connections enables precise localization of tissue regions while preserving spatial details.

### 3. Image Classification (CNN)
A custom convolutional neural network is used for classification. The model learns hierarchical feature representations from the original ground-truth masks to improve classification accuracy.

### 4. Evaluation
The framework is evaluated using standard performance metrics, including accuracy and confusion matrix analysis. These metrics are used to assess both segmentation quality and classification effectiveness.

---

## 🚀 Workflow

- Load and preprocess dataset (images and masks)
- Train U-Net model for segmentation
- Generate segmented outputs using ground-truth supervision
- Train CNN classifier on segmented results
- Evaluate performance using accuracy and confusion matrix

---

## 📊 Dataset

The dataset used in this study is available from the University of Queensland:

https://espace.library.uq.edu.au/view/UQ:8be4bd0

---

## 🧠 Method Summary

This framework integrates segmentation and classification into a unified pipeline for histopathological image analysis. The U-Net model captures fine-grained spatial structures through supervised segmentation, while the CNN uses the original ground-truth masks to learn discriminative features for accurate classification.

---

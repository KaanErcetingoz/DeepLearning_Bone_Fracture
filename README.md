# Bone Fracture Detection Using X-ray Images

This project leverages deep learning and machine learning techniques to detect bone fractures from multi-region X-ray images. It is built using the dataset from Fracture Multi-Region X-ray Data.

## Overview

Bone fractures are a common medical condition that require accurate and timely diagnosis. This project automates fracture detection using X-ray images, potentially assisting radiologists and reducing diagnostic errors. The implementation involves a combination of convolutional neural networks (CNNs) and traditional machine learning techniques to achieve high accuracy and efficiency.

## Dataset

The dataset used in this project is the Fracture Multi-Region X-ray Data, which can be accessed [here](https://www.kaggle.com/datasets/bmadushanirodrigo/fracture-multi-region-x-ray-data).
- **Base Directory:** `base_dir = 'https://www.kaggle.com/datasets/bmadushanirodrigo/fracture-multi-region-x-ray-data'`
- **Images:** The dataset contains X-ray images categorized as fractured or non-fractured.
- **Regions:** Multi-region images are provided, covering various anatomical areas.

## Methodology

The workflow consists of the following steps:

1. **Data Preprocessing:**
    - Resizing and normalizing the X-ray images.
    - Splitting the data into training, validation, and test sets.
    - Data augmentation to enhance model generalization.
2. **Model Training:**
    - A CNN model (e.g., ResNet, EfficientNet) is trained on the preprocessed images.
    - Transfer learning is utilized for better performance on limited data.
3. **Machine Learning Integration:**
    - Features are extracted using CNNs and used to train machine learning classifiers (e.g., SVM, Random Forest).
4. **Evaluation:**
    - Models are evaluated using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

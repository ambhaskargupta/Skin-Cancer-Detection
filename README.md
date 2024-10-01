# Skin-Cancer-Detection
Skin Cancer Detection using Convolutional Neural Networks (CNN)

This repository provides a skin cancer detection system built using Convolutional Neural Networks (CNN). The project focuses on classifying skin lesion images into malignant (cancerous) and benign (non-cancerous) categories. The repository demonstrates two approaches:

Basic CNN Architecture: A custom CNN model built from scratch to classify skin lesion images. This model includes essential CNN layers such as convolutional, pooling, and fully connected layers, and serves as an introduction to skin lesion classification using deep learning.

Data Augmentation: Techniques such as random rotations, flips, zooming, and brightness adjustments are used to artificially increase the training data and prevent overfitting.

# Features
Basic CNN Model: Implementation of a simple yet effective CNN model for classifying skin lesions as benign or malignant.

Overfitting Mitigation: The impact of data augmentation on overfitting is explored by comparing training and validation performance with and without augmentation.

Data Preprocessing: Automated scripts for resizing, normalizing, and augmenting the input images to improve the model’s generalization capabilities.

Performance Evaluation: Metrics such as accuracy, precision, recall  are used to evaluate and compare both models.


# Results
Data augmentation played a crucial role in reducing overfitting and improving the generalization capability of the CNN model. The custom architecture achieved competitive results in classifying skin lesions, demonstrating the efficacy of deep learning techniques when combined with proper data augmentation strategies.


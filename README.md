# Birdwatching: Object Detection and Classification

This project focuses on solving a core computer vision task: **object detection and classification**.  
The goal is to detect birds in images by predicting bounding boxes and classifying each bird into its species.

## Overview

Unlike standard image classification tasks, this project requires:
- **Localization**: Predicting bounding box coordinates for the bird  
- **Classification**: Identifying the bird species  

The model outputs:
- Bounding box coordinates (`x_min`, `y_min`, `x_max`, `y_max`)
- Predicted class label
- Confidence score

## Dataset

- Provided by the course
- Includes:
  - **Training set**
  - **Validation set**
  - **Test set (Kaggle for evaluation)**

Each image contains a **single bird**, but evaluation supports multiple objects.
# CNN-Based Manufacturing Defect Classification

## Project Overview
This project builds a CNN-based computer vision model to classify manufacturing product surface images into four categories:

- Normal
- Scratch
- Dent
- Stain

The objective is to automate defect detection using image classification.

---

## Task 1: Problem Identification
This dataset represents a **multi-class image classification problem** because each image belongs to one of four predefined categories.

It is not object detection because no bounding boxes are required, and it is not segmentation because no pixel-level annotations are provided.

---

## Task 2: Dataset Exploration

### Number of Classes
4 classes:
- Normal
- Scratch
- Dent
- Stain

### Images per Class
- Normal: 120
- Scratch: 120
- Dent: 120
- Stain: 120

Total Images: **480**

### Image Dimensions
All images are:
**96 × 96 × 3 (RGB)**

### Dataset Balance
The dataset is balanced with equal images in each class.

---

## Task 6: CNN Concept Explanation

### What is convolution?
Convolution is a process where a filter moves over an image to detect important visual features such as edges, textures, and shapes.

### Why is pooling used?
Pooling reduces feature map size, improves efficiency, and helps prevent overfitting.

### Why is ReLU used?
ReLU helps the model learn non-linear patterns efficiently and speeds up training.

### Why are CNNs better for images?
CNNs automatically detect spatial patterns and require fewer parameters than regular feed-forward networks.

---

## Task 7: Business Use Case Mapping

### Manufacturing Quality Inspection
This solution can be used in manufacturing industries for automated defect detection.

Benefits:
- Faster inspection
- Reduced manual effort
- Early defect detection
- Better product quality
- Reduced waste

Applications:
- Automobile manufacturing
- Electronics inspection
- Metal surface quality control

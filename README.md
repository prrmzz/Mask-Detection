# Mask-Detection
1. Algorithm
This project uses a Convolutional Neural Network (CNN) to classify images into two categories:

With Mask
Without Mask
Key Steps:
Data Preparation:

Images are cropped using bounding box annotations provided in XML files.
Cropped images are categorized into two folders: with_mask and without_mask.
Data Augmentation:

Techniques include rotation, zoom, flipping, and shifting to improve model generalization.
Model Architecture:

Three Convolutional Layers with ReLU activation and MaxPooling.
Batch Normalization and Dropout layers for regularization.
Fully connected Dense layers with Sigmoid activation for binary classification.
Training:

Optimizer: Adam with a learning rate of 0.0001.
Loss Function: Binary Crossentropy.
Callbacks: Early stopping and learning rate reduction to prevent overfitting.
2. Results
Training and Validation Accuracy:

Training Accuracy: 81.58% (Epoch 17)
Validation Accuracy: 79.36% (Epoch 17)
Loss:

Training Loss: 0.4491
Validation Loss: 1.8552

# Solar Cell Defect Classification using EfficientNetB0

Deep learning project for automatic classification of solar cell defects using TensorFlow and EfficientNetB0.

## Overview

This project classifies different types of defects on solar cells using transfer learning. The workflow includes:

- Dataset preprocessing
- Data augmentation
- Train/Validation split
- Hyperparameter optimization with Keras Tuner
- Model training using EfficientNetB0
- Performance evaluation
- Prediction on unseen test images

---

## Defect Classes

The dataset contains 12 different defect categories such as:

- Crack
- Fragment
- Scratch
- Printing Error
- Corner
- Vertical Dislocation
- ...

---

## Technologies

- Python
- TensorFlow / Keras
- EfficientNetB0
- Keras Tuner
- Albumentations
- OpenCV
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib

---

## Model Architecture

- EfficientNetB0 (ImageNet pretrained)
- Global Average Pooling
- Dense Layer
- Dropout
- Softmax Output

Training features:

- Transfer Learning
- Fine-tuning
- Focal Loss
- Class Weights
- Early Stopping
- ReduceLROnPlateau
- Learning Rate Scheduler

---

## Data Augmentation

Albumentations was used to improve dataset diversity.

Applied augmentations:

- Horizontal Flip
- Vertical Flip
- Random Rotation
- Brightness & Contrast
- Random Scaling
- Motion Blur
- Gaussian Noise

---

## Hyperparameter Optimization

Hyperparameters were optimized using Keras Tuner Random Search.

Optimized parameters include:

- Learning Rate
- Dense Layer Size
- Dropout Rate

---

## Evaluation

Model performance was evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1 Score

---

## Future Improvements

- Vision Transformer (ViT)
- EfficientNetV2
- Grad-CAM visualization
- TensorBoard logging
- ONNX / TensorRT export
- Web deployment with Streamlit

---

## Author

Burak Yıldırım

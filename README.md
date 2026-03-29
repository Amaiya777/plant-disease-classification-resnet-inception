# Plant Disease Classification using CNN Architectures

##  Overview
This project implements an image classification system to detect plant diseases using deep learning. It uses transfer learning with ResNet50 and InceptionV3 and compares their performance on the PlantVillage dataset.

---

##  Features
- Image classification using CNNs
- Transfer learning with pretrained models
- Comparison of ResNet50 and InceptionV3
- Data augmentation for improved generalization
- Model evaluation using accuracy, loss curves, and confusion matrix

---

##  Models Used
- ResNet50 (Residual Network)
- InceptionV3 (GoogLeNet Architecture)

---

##  Dataset
- Dataset: PlantVillage
- Classes: 4
- Training Images: ~3000
- Validation Images: ~600
- Test Images: ~500

>  Dataset not included due to size.

---

##  Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

---

##  Training Details
- Used pretrained ImageNet weights
- Frozen base layers for transfer learning
- Applied data augmentation:
  - Rotation
  - Zoom
  - Horizontal flip
- Early stopping used to prevent overfitting

---

##  Results
- Achieved ~70% validation accuracy
- Generated confusion matrix for performance evaluation
- Compared performance of ResNet50 and InceptionV3

---

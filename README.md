# HemaVision-AI
Explainable Malaria Diagnosis System using MobileNetV2, Random Forest, and Grad-CAM

## Overview

HemaVision AI is an explainable computer vision framework for automated malaria diagnosis from microscopic blood smear images. The system combines deep feature extraction using MobileNetV2 with a Random Forest ensemble classifier to accurately distinguish parasitized and uninfected red blood cells.

To improve interpretability, Grad-CAM is integrated to highlight the image regions influencing model predictions, providing visual explanations that can assist clinical review.

---

## Features

* Hybrid CNN and Random Forest framework
* MobileNetV2-based deep feature extraction
* Random Forest ensemble classification
* Data augmentation and image preprocessing
* Class balancing to improve robustness
* Grad-CAM explainability for visual interpretation
* Automated clinical report generation

---

## Dataset

**NIH Malaria Cell Images Dataset**

* Approximately 27,558 cell images
* Binary classification task:

  * Parasitized
  * Uninfected

---

## Methodology

1. Image preprocessing and resizing
2. Pixel normalization and data augmentation
3. Feature extraction using MobileNetV2
4. Classification using Random Forest
5. Performance evaluation on unseen samples
6. Grad-CAM visualization for model interpretability

---

## Performance

| Metric   | Value |
| -------- | ----- |
| Accuracy | 91%   |
| Recall   | 93%   |

---

## Technologies Used

* Python
* TensorFlow
* MobileNetV2
* Random Forest
* OpenCV
* Grad-CAM
* NumPy
* Matplotlib
* Scikit-learn

---

## Applications

* Automated malaria screening
* Computer-aided diagnosis
* Explainable AI in healthcare
* Clinical decision support systems

---

## Future Work

* Multi-class parasite stage classification
* Web-based deployment
* Lightweight mobile inference
* Integration with clinical workflow systems


---

## Author

Developed as a machine learning and explainable AI project for automated malaria diagnosis.

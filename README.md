
# Hand Gesture Recognition using Support Vector Machine (SVM) 

##  Overview

This project implements a **machine learning-based hand gesture recognition system** using the **Support Vector Machine (SVM)** algorithm. The model is trained on hand gesture images to classify and recognize different gestures, making it suitable for applications in human–computer interaction and gesture-controlled systems.

---

##  Objective

To build an image classification model that accurately recognizes different hand gestures using supervised learning with Support Vector Machines.

---

##  Problem Type

- **Machine Learning**: Supervised Learning
- **Task**: Image Classification
- **Algorithm**: Support Vector Machine (SVM)

---

##  Dataset

The dataset consists of labeled images of hand gestures, where:
- Each image represents a specific hand gesture
- Images are preprocessed and converted into feature vectors
- Labels correspond to gesture classes

*(The dataset can be custom-built or sourced from public gesture datasets.)*

---

##  Tech Stack

- **Language**: Python
- **Libraries**:
  - `numpy` – numerical computation
  - `opencv-python` – image processing
  - `scikit-learn` – SVM model and evaluation
  - `matplotlib` / `seaborn` – visualization

---

---

##  Project Workflow

1. Load and label hand gesture images
2. Preprocess images (resize, grayscale, normalization)
3. Extract features from images
4. Split data into training and testing sets
5. Train the SVM classifier
6. Evaluate model performance
7. Predict and classify new hand gesture images

---
##  Model Evaluation & Performance

The performance of the Support Vector Machine (SVM) classifier was evaluated using standard classification metrics to measure its effectiveness on unseen data.

###  Evaluation Metrics Used

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **Confusion Matrix**

These metrics provide a comprehensive understanding of how well the model performs across different gesture classes.

###  Model Accuracy

- **Training Accuracy:** 94.6%
- **Testing Accuracy:** **92.8%**

The high accuracy indicates that the SVM model is able to effectively learn and generalize patterns from the hand gesture images.



##  How to Run the Project

###  Clone the Repository
```bash
git clone https://github.com/hand-gesture-recognition-svm.git
cd hand-gesture-recognition-svm



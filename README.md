# 🧠 Computer Vision Labs

This repository contains a collection of **Computer Vision labs** designed to explore both fundamental and advanced concepts in **image processing** and **image classification** — from basic point operations to deep feature extraction.

---

## 📚 Table of Contents

- [Overview](#-overview)  
- [Lab 1 - Point Processing](#-lab-1---point-processing)  
- [Lab 2 - Image Convolution](#-lab-2---image-convolution)  
- [Lab 3 - SIFT and Bag of Visual Words (BoVW)](#-lab-3---sift-and-bag-of-visual-words-bovw)  
- [Lab 4 - Image Classification Using Deep Features](#-lab-4---image-classification-using-deep-features)  
- [Dependencies](#-dependencies)  
- [How to Run](#️-how-to-run)  
- [Results](#-results)  
- [Author](#-author)

---

## 🧠 Overview

These labs progressively introduce key techniques in **Computer Vision** and **Image Analysis**, including:

- Point and intensity transformations  
- Image filtering using convolution  
- Feature detection and description with **SIFT**  
- **Bag of Visual Words (BoVW)** model for classical image classification  
- Deep feature extraction using pretrained **CNN** models  

🎯 **Goal:**  
To understand both **classical computer vision pipelines** and **modern deep learning-based approaches**.

---

## 🧪 Lab 1 - Point Processing

### 🎯 Objective
Apply **point-based transformations** to enhance image quality and contrast.

### 🧩 Topics Covered
- Negative transformation  
- Log and Power-Law (Gamma) transformation  
- Contrast stretching  
- Histogram equalization  

### 🛠️ Tools
`OpenCV`, `NumPy`, `Matplotlib`

---

## 🌀 Lab 2 - Image Convolution

### 🎯 Objective
Understand the **spatial filtering process** and how convolution affects image appearance.

### 🧩 Topics Covered
- Custom kernel convolution  
- Smoothing filters (Average, Gaussian)  
- Sharpening filters  
- Edge detection (Sobel, Prewitt, Laplacian)

### 🛠️ Tools
`OpenCV`, `NumPy`, `Matplotlib`

---

## 🌼 Lab 3 - SIFT and Bag of Visual Words (BoVW)

### 🎯 Objective
Perform **feature-based image classification** using SIFT descriptors and a Bag of Visual Words model.

### 🧩 Topics Covered
- SIFT feature detection and description  
- Visual vocabulary construction using **K-Means clustering**  
- Histogram representation of images  
- Classification using **SVM** or **Logistic Regression**

### 🛠️ Tools
`OpenCV (SIFT)`, `scikit-learn`, `NumPy`, `Matplotlib`

---

## 🤖 Lab 4 - Image Classification Using Deep Features

### 🎯 Objective
Leverage **pretrained CNN models** to extract deep features for image classification.

### 🧩 Topics Covered
- Feature extraction using models like **VGG16** or **ResNet50**  
- Flattening and saving deep feature vectors  
- Training classifiers (SVM, Softmax, etc.) on extracted features  
- Comparing deep features vs. classical features  

### 🛠️ Tools
`TensorFlow / Keras`, `scikit-learn`, `NumPy`, `Matplotlib`

---

## ⚙️ Dependencies

Install the following Python libraries before running the labs:

```bash
pip install opencv-python numpy matplotlib scikit-learn tensorflow
```

---

## ▶️ How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MohemedAmine/Computer-Vision.git
   cd Computer-Vision
   ```

2. **Open each lab notebook or script** (e.g., `lab1_point_processing.ipynb`) in **Jupyter Notebook** or **VSCode**.

3. **Run all cells** or execute the Python files sequentially.

---

## 📊 Results

Each lab includes visual outputs such as:

- Transformed and enhanced images  
- Filtered and edge-detected images  
- Feature keypoints and matching results  
- Confusion matrices and accuracy comparisons between models  

---

## 👨‍💻 Author

**Name:** Mohamed Amine Ouled Said  
**Institution:** École Supérieure en Informatique (ESI SBA)  
**Course:** Computer Vision Laboratory  

⭐ *If you find this repository helpful, don’t forget to star it!*

---

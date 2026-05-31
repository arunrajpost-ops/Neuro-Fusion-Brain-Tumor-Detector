# 🧠 NeuroFusion

## A Deep Learning Approach for Brain Tumor Classification via CT-MRI Image Fusion

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![Flask](https://img.shields.io/badge/Flask-WebApp-green)
![OpenCV](https://img.shields.io/badge/OpenCV-ComputerVision-red)
![Medical Imaging](https://img.shields.io/badge/Medical-Imaging-purple)

---

## 📌 Overview

NeuroFusion is an AI-powered medical imaging system designed to improve brain tumor detection through multimodal CT-MRI image fusion. The project integrates advanced image processing and deep learning techniques to combine the strengths of Computed Tomography (CT) and Magnetic Resonance Imaging (MRI) into a single enhanced diagnostic image.

The system leverages Discrete Wavelet Transform (DWT), VGG-19 Transfer Learning, and Watershed Segmentation to provide accurate tumor visualization and support medical professionals in diagnostic decision-making.

---

## 🎯 Objectives

* Integrate CT and MRI modalities into a unified diagnostic image.
* Improve tumor boundary visualization and detection accuracy.
* Reduce manual interpretation effort for radiologists.
* Automate image registration, fusion, and segmentation workflows.
* Develop a user-friendly platform for medical image analysis.

---

## ❗ Problem Statement

Traditional medical imaging systems require clinicians to analyze CT and MRI scans separately. This process is time-consuming and can lead to missed diagnostic details.

Current image fusion methods often suffer from:

* Loss of critical tumor information
* Low image contrast
* Feature blurring
* Noise and artifacts
* Poor multimodal integration

NeuroFusion addresses these limitations through intelligent image fusion and automated tumor segmentation.

---

## 🏗️ System Architecture

```text
CT Scan + MRI Scan
        │
        ▼
 Image Registration
        │
        ▼
 DWT-Based Fusion
        │
        ▼
 VGG-19 Feature Extraction
        │
        ▼
 Enhanced Fused Image
        │
        ▼
 Watershed Segmentation
        │
        ▼
 Tumor Detection Output
```

---

## ⚙️ Methodology

### 1️⃣ Image Registration

CT and MRI scans are spatially aligned using landmark-based registration techniques to ensure accurate correspondence between anatomical structures.

### 2️⃣ Image Fusion

The registered images undergo:

* Discrete Wavelet Transform (DWT)
* Deep Feature Extraction using VGG-19

to preserve both structural and soft tissue information.

### 3️⃣ Tumor Segmentation

Watershed Segmentation is applied to identify and isolate tumor regions from the fused image.

### 4️⃣ Validation

A confidence-based validation mechanism evaluates the reliability of segmented regions before displaying results.

---

## 🚀 Key Features

✅ Multimodal CT-MRI Fusion

✅ Landmark-Based Image Registration

✅ VGG-19 Transfer Learning

✅ DWT-Based Image Processing

✅ Automated Tumor Segmentation

✅ Flask Web Application

✅ Tkinter Desktop Application

✅ Enhanced Diagnostic Visualization

✅ Clinician-Friendly Interface

---

## 🛠️ Technology Stack

### Programming Language

* Python

### Deep Learning

* TensorFlow
* Keras
* VGG-19 Transfer Learning

### Machine Learning

* Scikit-Learn

### Image Processing

* OpenCV
* Scikit-Image
* PyWavelets

### Web Development

* Flask
* HTML
* CSS
* JavaScript

### Desktop Application

* Tkinter

### Development Tools

* VS Code
* Jupyter Notebook
* Git

---

## 📊 Results

The proposed system successfully:

* Fused CT and MRI images into a single enhanced image.
* Improved visualization of tumor boundaries.
* Automated registration and segmentation workflows.
* Reduced diagnostic effort through AI-assisted analysis.
* Generated clinically interpretable outputs.

---

## 📷 Screenshots

### Home Page

(Add Screenshot)

### CT & MRI Upload Interface

(Add Screenshot)

### Registration Process

(Add Screenshot)

### Fused Image Output

(Add Screenshot)

### Tumor Segmentation Result

(Add Screenshot)

---

## 📂 Project Structure

```text
NeuroFusion/
│
├── app.py
├── static/
├── templates/
├── dataset/
├── models/
├── fusion/
├── segmentation/
├── registration/
├── results/
├── requirements.txt
└── README.md
```

---

## 💡 Advantages

* Improved Brain Tumor Detection
* Better Image Quality
* Accurate Tumor Boundary Identification
* Reduced Manual Analysis
* Faster Clinical Decision Support
* Scalable AI-Based Solution

---

## 🔮 Future Scope

* Integration with PET-CT Imaging
* U-Net Based Segmentation
* Vision Transformer (ViT) Integration
* Cloud Deployment
* Electronic Health Record (EHR) Integration
* Real-Time Clinical Decision Support Systems

---

## 👨‍💻 Contributors

* S. Arun Raj
* Chundi Sai Loukhya
* G. Sai Siddharth Naidu
* P. Vishal Sai Munukuntla
* Veerath Lakshitha

---

## 🎓 Institution

**MLR Institute of Technology**
Department of Computer Science & Engineering (Artificial Intelligence & Machine Learning)

Hyderabad, Telangana, India

---

## 📄 Research Work

**Title:**
**NeuroFusion: A Deep Learning Approach for Brain Tumor Classification via CT-MRI Image Fusion**

This project combines Deep Learning, Image Fusion, Transfer Learning, and Medical Image Processing to support accurate and efficient brain tumor diagnosis.

---

## 📜 License

This project is developed for academic and research purposes only.

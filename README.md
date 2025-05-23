# VGG16-Based Face Recognition Using Transfer Learning

## 📌 Project Overview

This project implements a **face recognition system** using **transfer learning with VGG16** as the base model. It fine-tunes a deep convolutional network on a custom dataset of celebrity faces and performs prediction using OpenCV for testing with randomized images.

---

## 🎯 Key Features

- Uses **VGG16 pretrained on ImageNet**
- Fine-tunes top layers for binary classification (e.g., Elton John vs. Ben Affleck)
- Utilizes **Keras Functional API**
- Applies **ImageDataGenerator** for data augmentation
- Trains and evaluates the model on custom dataset
- Randomly selects and predicts a face image using **OpenCV**
- Annotates image with prediction result in real time

---

## 🧰 Technologies Used

- Python
- TensorFlow/Keras
- OpenCV
- NumPy
- Transfer Learning (VGG16)
- ImageDataGenerator for preprocessing
- Matplotlib (for plotting metrics, optional)

---

## 🗂️ Directory Structure

```
.
├── train/                    # Training dataset (organized by class folders)
├── val/                      # Validation dataset (organized by class folders)
├── face_recog_vgg.h5         # Saved model
├── facerecognition.ipynb     # Main Jupyter notebook
├── hybrid.jpg                # Test image (optional)
└── README.md                 # This file
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- TensorFlow/Keras
- OpenCV
- NumPy

### Installation

```bash
pip install tensorflow opencv-python numpy
```

### Running the Project

1. Organize dataset in `train/` and `val/` folders (each with subfolders per class)
2. Run the notebook step-by-step
3. Model is saved as `face_recog_vgg.h5`
4. Load a random image from `val/` to test the prediction

---

## ✅ Highlights for Recruiters

- Demonstrates **deep learning model construction** with custom head layers
- Applies **best practices** in transfer learning and fine-tuning
- Implements **real-time inference logic** with OpenCV
- Capable of generalizing to multi-class classification with minimal changes
- Reflects strong command of **Keras Functional API**, model callbacks, and preprocessing

---
## 👤 Author

**Sai Jayanth Rajamahendram**  
Cloud | DevOps | ML Enthusiast  
[LinkedIn](https://www.linkedin.com/in/saijayanthraj/) | [GitHub](https://github.com/saijayanth41)

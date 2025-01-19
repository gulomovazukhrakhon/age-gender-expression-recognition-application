# Age, Gender, and Expression Recognition Application

## Overview
This project is an AI-powered mobile application capable of recognizing **age**, **gender**, and **facial expressions** from images. Built using **PyTorch** for model training and **Android Studio** for mobile application development, the project demonstrates the integration of a deep learning model with edge deployment on Android devices.

The application can predict:
- **Age Groups**: Child, Teen, Young Adult, Adult, Elderly.
- **Gender**: Male or Female.
- **Expressions**: Happy, Sad, Angry, Neutral, Surprised.

The system is optimized for real-world applications, supporting lightweight, efficient edge deployment.

---

## Features
- Multi-task Deep Learning Model based on **ResNet-18**.
- Real-time predictions using a mobile-friendly interface.
- Lightweight deployment with **TorchScript** and **quantization**.
- Supports image input from camera or gallery.

---

## Technologies Used
- **Programming Languages**: Python, Java
- **Frameworks**:
  - **PyTorch** for model development.
  - **Android Studio** for application development.
- **Datasets**:
  - [AgeUTK](https://www.kaggle.com/datasets/roshan81/ageutk) for age and gender.
  - [FER 2013](https://www.kaggle.com/datasets/ananthu017/emotion-detection-fer) for emotion detection.

---

## Prerequisites
- Python 3.8+
- Android Studio
- PyTorch 1.12+
- TorchVision 0.13+
- Device with Android 8.0+

## How It Works
* Model Training:
  A multi-head ResNet-18 model was trained to predict age, gender, and expressions simultaneously.

* Edge Deployment:
  The trained model was converted to TorchScript and quantized for efficient mobile deployment.

* Mobile Application:
  The application allows users to take a photo or select an image for predictions.

* Real-World Testing:
  The model was tested on real-world images, achieving high accuracy for most predictions.

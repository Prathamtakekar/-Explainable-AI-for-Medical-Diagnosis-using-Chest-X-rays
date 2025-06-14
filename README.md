# 🧠 Explainable AI for Medical Diagnosis using Chest X-rays

This project focuses on developing a deep learning model that not only detects pneumonia from chest X-ray images but also explains its predictions using **Grad-CAM** visualizations. It aims to bridge the gap between medical imaging AI and transparency in decision-making — a crucial step for real-world healthcare applications.

## 🚀 Project Highlights

- 🔍 **Task**: Classify Chest X-rays as NORMAL or PNEUMONIA
- 🧠 **Model**: ResNet-18 (Transfer Learning)
- 📊 **Explainability**: Grad-CAM for heatmap visualization of critical regions
- 📦 **Dataset**: [Chest X-ray Pneumonia Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- 🛠️ **Technologies**: PyTorch, Torchvision, OpenCV, Matplotlib, PIL
- 📍 **Environment**: Google Colab, kagglehub for automatic dataset download

## 💡 Features

- ✅ High-accuracy model using pretrained ResNet
- ✅ Automatic download and setup of medical dataset via `kagglehub`
- ✅ Explainable predictions using Grad-CAM heatmaps
- ✅ Code-ready for Colab use and extensible to other imaging datasets

## 📷 Example Output

<p align="center">
  <img src="output_example.png" alt="Grad-CAM Example" width="400"/>
</p>

## 📁 Structure


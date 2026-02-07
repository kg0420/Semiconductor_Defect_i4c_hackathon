# AI Wafer Defect Classification System

### IESA i4C DeepTech Hackathon Submission

---

## 📌 Overview

This project presents an deep learning–based automated wafer defect classification system developed for the **IESA i4C DeepTech Hackathon**. The system uses modern computer vision techniques and a ConvNeXt neural network to detect and classify semiconductor wafer defects from wafer map images.

The goal is to replace slow and error-prone manual inspection with an accurate, scalable, and explainable AI solution suitable for smart manufacturing environments.

---

## 🎯 Problem Statement

Semiconductor wafer inspection requires extremely high precision. Traditional inspection methods are:

* Manual and time-consuming
* Prone to human error
* Inefficient for large-scale production
* Unable to detect complex defect patterns reliably

This project addresses the need for an real-time automated defect classification system using deep learning.

---

## 💡 Proposed Solution

Our solution builds an AI pipeline that:

* Converts raw wafer maps into structured image representations
* Applies preprocessing and data augmentation
* Trains a ConvNeXt deep learning model
* Performs multi-class wafer defect classification
* Provides explainable AI visualizations using Grad-CAM
* Analyzes learned feature spaces with t-SNE

The system achieves high classification performance while remaining scalable and interpretable.

---

## 🧠 Model Architecture

We use **ConvNeXt-Tiny**, a modern convolutional neural network optimized for visual pattern recognition.

Key features:

* Transfer learning from pretrained weights
* Fine-tuning for wafer defect classification
* Mixed precision training for speed and efficiency
* Robust handling of imbalanced datasets

---

## 📂 Dataset

The project uses the **Large Scale Wafer Map Dataset (LSWMD)**, which contains labeled wafer defect patterns such as:

* Center
* Donut
* Edge-Loc
* Edge-Ring
* Scratch
* Random
* Near-Full
* Clean wafers

Dataset preprocessing includes label cleaning, stratified splitting, and wafer-to-image conversion.

---

## ⚙️ Technology Stack

**Languages & Frameworks**

* Python
* PyTorch
* OpenCV
* Albumentations

**Machine Learning**

* ConvNeXt CNN architecture
* Transfer learning
* Mixed precision training
* Data augmentation
* Weighted sampling for imbalance handling

**Visualization**

* Grad-CAM explainability
* t-SNE feature visualization

---

## 🏗️ Project Structure

```
├── data/                  # Dataset folders (Train / Validation / Test)
├── notebooks/             # Experiment notebooks
└── README.md
```

---

## 🚀 Installation

```bash
git clone https://github.com/your-username/i4c-wafer-defect-ai
cd i4c-wafer-defect-ai
pip install -r requirements.txt
```




---

## 📊 Results

The model demonstrates strong performance across multiple defect classes:

* High macro F1-score
* Accurate classification of rare defect patterns
* Clear class separation in feature space
* Interpretable Grad-CAM heatmaps

---

## 🌍 Impact

This system can:

* Automate semiconductor wafer inspection
* Reduce production losses due to defects
* Improve manufacturing efficiency
* Support Industry 4.0 smart factories
* Enable scalable AI-driven quality control

---

## 🔮 Future Work

* Real-time deployment in production lines
* Web dashboard for monitoring defects
* Ensemble deep learning models
* Continuous learning with new data
* Edge deployment for industrial systems

---

## 📚 References

* LSWMD Dataset
* ConvNeXt: A ConvNet for the 2020s (arXiv)
* Grad-CAM Explainability Paper
* Deep Learning for Industrial Inspection Surveys

---

## 👥 Team

**IESA i4C Hackathon Team**

* Team Leader: Krish Gupta
* Team Name: Innovators 

---

## 📎 Links

* GitHub Repository: *Add your repo link here*
---

## 📜 License

This project is developed for hackathon and academic purposes.

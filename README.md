# 🩺 Skin Cancer Classification

[![Built with Python](https://img.shields.io/badge/Built%20with-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Framework PyTorch](https://img.shields.io/badge/Framework-PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![Deep Learning](https://img.shields.io/badge/Model-Convolutional%20Neural%20Networks-blue?style=for-the-badge&logo=pytorch&logoColor=white)]()
[![Explainability](https://img.shields.io/badge/Explainability-Grad--CAM-orange?style=for-the-badge&logo=visualstudio&logoColor=white)]()
[![Notebook](https://img.shields.io/badge/Developed%20on-Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/)
[![Dataset](https://img.shields.io/badge/Dataset-10K%2B%20Dermatoscopic%20Images-brightgreen?style=for-the-badge&logo=databricks)]()

**Skin Cancer Classification** is a deep learning–based system built with **Python** and **PyTorch** to automatically identify multiple skin lesion types from a **10K+ dermatoscopic image dataset**. It incorporates **data augmentation**, **hyperparameter tuning**, and **Grad-CAM visualizations** to improve model robustness and provide interpretable insights into diagnostic regions influencing predictions.

> 📊 **Achieved 81% validation accuracy.**

---

## 🚀 Features

### 🧠 Multi-Class Lesion Classification
- Classifies multiple skin lesion types from dermatoscopic images  
- End-to-end CNN training pipeline in PyTorch  
- GPU-accelerated training support  

### 🖼️ Data Preprocessing & Augmentation
- Image resizing and normalization  
- Random horizontal/vertical flips  
- Rotation and scaling transformations  
- Improves generalization and robustness  

### ⚙️ Model Architecture
- Convolutional layers for spatial feature extraction  
- Batch normalization & dropout for regularization  
- Fully connected layers for classification  
- Softmax output for multi-class probability prediction  

### 🔥 Grad-CAM Interpretability
- Generates heatmaps highlighting important regions  
- Visualizes model attention on lesion areas  
- Improves transparency in medical AI predictions  

### 📊 Training & Optimization
- Train/validation split  
- Cross-entropy loss  
- Adam optimizer  
- Learning rate tuning and regularization  

---

## 🛠 Tech Stack

- **Language**: Python  
- **Deep Learning Framework**: PyTorch  
- **Environment**: Google Colab  
- **Visualization**: Matplotlib, Grad-CAM  
- **Hardware**: GPU-accelerated training  

---

## 🧬 Model Pipeline

1. **Dataset Loading**
   - Load 10K+ dermatoscopic images  
   - Apply preprocessing & normalization  

2. **Data Augmentation**
   - Randomized transformations during training  

3. **Model Training**
   - Forward pass → Loss computation → Backpropagation  
   - Optimizer updates weights  
   - Validation monitoring  

4. **Evaluation & Interpretation**
   - Generate predictions on unseen data  
   - Apply Grad-CAM to visualize activation maps  
   - Overlay heatmaps on original images

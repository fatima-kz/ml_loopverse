# ml_loopverse
# EuroSAT Land Use Classification — ML Competition

## 📌 Overview
This project is developed for the **Loopverse EuroSAT ML Competition**.  
The goal is to classify satellite images into land use/land cover categories using a **Convolutional Neural Network (CNN) built from scratch** — without using pretrained models like ResNet, VGG, or ViT.

We follow the exact competition tasks:
1. Data Cleaning & Preprocessing  
2. Feature Extraction & Visualization  
3. CNN Model from Scratch  
4. Performance Improvements  
5. Model Evaluation  
6. Analysis & Report Generation

---

## 📂 Dataset
The dataset is based on **EuroSAT RGB & Multispectral (MS)** images.

- **Original formats**: `.tif`, `.png`, `.jpg`  
- **Classes**: Multiple land use categories (e.g., Residential, Forest, Industrial, River, etc.)  
- **Source**: Provided by competition organizers

---

## 🛠️ Setup Instructions
Run in **Google Colab** (recommended) with GPU runtime.

### Install dependencies:
```bash
pip install tensorflow opencv-python scikit-learn matplotlib seaborn reportlab

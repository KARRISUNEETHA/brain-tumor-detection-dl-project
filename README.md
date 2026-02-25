# 🧠 Brain Tumor Detection Using Deep Learning

## 📌 Project Overview

Brain tumors are one of the most serious neurological disorders and require early and accurate diagnosis. Manual analysis of MRI scans is time-consuming and may lead to human errors.

This project develops a Deep Learning-based system using Convolutional Neural Networks (CNN) to automatically classify brain MRI images into:

- Tumor
- No Tumor

The system assists in faster and more consistent medical diagnosis.

---

## 🎯 Objectives

- Develop a CNN model for automated brain tumor detection
- Reduce dependency on manual MRI interpretation
- Improve diagnostic accuracy using Deep Learning
- Evaluate model performance using standard metrics

---

## 📂 Dataset Information

- **Dataset Name:** Brain MRI Images for Brain Tumor Detection
- **Source:** Kaggle
- **Classes:** Tumor / No Tumor
- **Image Format:** JPG

Dataset Link:
https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection

---

## 🛠️ Technologies Used

- Python
- NumPy
- Matplotlib
- TensorFlow
- Keras
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Project Workflow

1. Data Collection  
   - Download MRI dataset from Kaggle  
   - Organize images into class folders  

2. Data Preprocessing  
   - Resize images to uniform dimensions  
   - Normalize pixel values  
   - Split dataset into training, validation, and testing sets  

3. Data Augmentation  
   - Rotation  
   - Horizontal flipping  
   - Zooming  
   - Image shifting  

4. Model Building  
   - Convolutional Layers  
   - ReLU Activation  
   - Max Pooling  
   - Flatten Layer  
   - Dense Layers  
   - Sigmoid Output Layer  

5. Model Training  
   - Loss Function: Binary Crossentropy  
   - Optimizer: Adam  
   - Trained for multiple epochs  

6. Model Evaluation  
   - Accuracy  
   - Precision  
   - Recall  
   - F1 Score  
   - Confusion Matrix  

---

## 🧠 Model Architecture

MRI Image  
↓  
Preprocessing  
↓  
CNN Layers  
↓  
Flatten  
↓  
Dense Layers  
↓  
Output (Tumor / No Tumor)

---

## 📊 Results

- Successfully trained a CNN model
- Achieved strong classification accuracy
- Generated confusion matrix
- Visualized training and validation accuracy graphs
- Model correctly classified majority of MRI images

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/brain-tumor-detection.git

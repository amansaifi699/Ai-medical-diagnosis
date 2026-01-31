# AI-Based Medical Diagnosis System (Chest X-ray)

## Overview
This project implements a deep learning–based medical image classification system
for analyzing Chest X-ray images. The goal is to classify images into categories
such as Normal, COVID-19, and Pneumonia using convolutional neural networks and
transfer learning techniques.

The project focuses on building an end-to-end machine learning pipeline including
data preprocessing, model training, evaluation, and visualization.

---

## Technologies Used
- Python
- TensorFlow / Keras
- Convolutional Neural Networks (CNN)
- Transfer Learning (ResNet50)
- NumPy, Pandas, Matplotlib
- Google Colab

---

## Project Structure
ai-medical-diagnosis/
├── data/ # Dataset is referenced but not stored in this repository
├── notebooks/ # Google Colab notebooks
├── docs/ # Sample outputs and visualizations
└── README.md

---

## Dataset
The dataset used in this project consists of Chest X-ray images for medical image
classification. Due to size constraints, the dataset is not included in this
repository.

You can use publicly available datasets such as:
- COVID-19 Radiography Database (Kaggle)

---

## How to Run
1. Open the notebook from the `notebooks/` directory in **Google Colab**
2. Upload or link the dataset in your Google Drive
3. Update the dataset path if required
4. Run the notebook cells sequentially

The models are trained in Google Colab due to limited local computational resources.

---

## Results
The project includes model performance evaluation and visualization techniques
such as Grad-CAM to highlight important regions in Chest X-ray images.

Sample output images are available in the `docs/` directory.

---

## Notes
- Trained model files and datasets are intentionally excluded from this repository
- This project was developed as an academic and learning-oriented implementation

---

## Author
Aman Saifi

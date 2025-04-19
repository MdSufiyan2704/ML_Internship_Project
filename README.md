# ML_Internship_Project

# 🌲 Forest Fire Detection using Deep Learning

This project was developed during my internship at **Edunet Foundation**, where I explored Machine Learning and Deep Learning techniques to address real-world challenges. The goal of this project is to build an intelligent system that can detect forest fires using image-based data, contributing to early fire warning systems and helping in environmental protection efforts.

---

## 🔍 Project Overview

- **Objective:** To detect forest fires from images using a Convolutional Neural Network (CNN).
- **Tech Stack:** Python, TensorFlow/Keras, OpenCV, NumPy, Matplotlib.
- **Model:** A custom CNN model trained on a labeled dataset of forest fire and non-fire images.
- **Accuracy:** Achieved high classification accuracy on validation and test datasets.
- **Deployment Ready:** The model can be integrated into real-time surveillance systems for fire detection.

---

## 🚀 Features

- Image classification (**Fire** vs. **No Fire**).
- Preprocessing pipeline with image resizing and normalization.
- Training and evaluation scripts included.
- Confusion matrix and performance metrics (accuracy, precision, recall).
- Easily extendable to multi-class or real-time detection.

---

## 📁 Dataset

- Used a public dataset consisting of images categorized as:
  - **Fire** – images with visible forest fires.
  - **No Fire** – safe forest environments.
- Data augmentation applied for improving generalization.

---

## 📌 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/your-username/Forest_Fire_Detection.git
cd Forest_Fire_Detection

# 2. Install dependencies
pip install -r requirements.txt

# 3. Train the model
python train.py

# 4. Test the model
python test.py

# 5. Predict on custom images
python predict.py --image path_to_image.jpg

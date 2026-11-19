Forest-Fire-Detection-using-CNN
A deep learning-based image classification project that uses Convolutional Neural Networks (CNN) to automatically detect forest fires from images. The aim is to support early detection and alert systems for wildfire prevention.

📖 Overview
Forest fires can have devastating impacts on the environment and biodiversity. This project uses a CNN-based image classification model to detect the presence of fire in forest imagery. It can be integrated into real-time drone or CCTV surveillance systems to automate fire detection.

✅ Features
Binary classification: Fire vs. No Fire
Custom CNN built using TensorFlow/Keras
Image preprocessing and augmentation
Evaluation using accuracy, confusion matrix, and classification report
Easily extendable for real-time use cases
🛠️ Tech Stack
Python
TensorFlow / Keras
NumPy, Pandas
Matplotlib, Seaborn
Jupyter Notebook
📂 Dataset
Source: Dataset
Classes:
'Fire' – images containing forest fires
'No_Fire' – normal forest landscapes
Note: The dataset is balanced and contains images in JPEG format.

🧠 Project Architecture
Input Image ➝ Preprocessing ➝ CNN Layers ➝ Dense Layers ➝ Output (Fire / No Fire)

📈 Model Performance
Accuracy: 95%+ on test set
Loss Function: Binary Crossentropy
Optimizer: Adam
Metrics: Accuracy, Precision, Recall, F1-Score

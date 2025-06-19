# 📝 Handwritten Odia Text Recognition

This project is a deep learning-based system to recognize handwritten Odia (ଓଡ଼ିଆ) characters using a Convolutional Neural Network (CNN). Built using TensorFlow, OpenCV, and Keras, it processes scanned character images and classifies them into their respective Odia script labels.

## 📌 Features

- Trained on 5,000+ handwritten samples
- Achieves ~92% classification accuracy
- Includes preprocessing (grayscale, binarization, normalization)
- Built with CNN using TensorFlow and Keras
- OpenCV used for image manipulation
- Modular and extendable notebook/scripts

## 📁 Project Structur

handwritten-odia-text-recognition/
├── notebooks/ - python notebooks/scriptsfor model training & testing and segmentation
├── scripts/ - Modular Python scripts for recognition
├── data/ - Folder to hold sample images
├── model/ - Trained CNN model (cnn_model.h5)
├── requirements.txt - Python dependencies
├── README.md - This documentation
└── .gitignore

## 🧪 Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Pandas, Matplotlib
- Jupyter Notebook

## 🔄 Preprocessing Pipeline

1. Image binarization & resizing
2. Normalization to 0–1 scale
3. Label encoding
4. Data split (train/test)

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/Hukl99/handwritten-odia-text-recognition.git

# Navigate to the project
cd handwritten-odia-text-recognition

# Install dependencies
pip install -r requirements.txt

# Run the notebook
Run the script GUI INTERFACE.py
```

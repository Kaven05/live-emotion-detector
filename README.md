# 🎭 Live Emotion Detector using Deep Learning

A real-time facial emotion detection system using OpenCV and a Convolutional Neural Network (CNN) model. This project detects faces from webcam feed and classifies emotions such as Happy, Sad, Angry, and more.

---

## 🧠 Features

- Real-time webcam emotion detection
- Face detection using Haar Cascade
- Emotion classification using pre-trained CNN (`fer.h5`)
- Supports 7 emotions:  
  `Angry`, `Disgust`, `Fear`, `Happy`, `Neutral`, `Sad`, `Surprise`

---

## 🛠️ Tech Stack

- Python 3.x
- OpenCV
- Keras (TensorFlow backend)
- NumPy

---

## 📂 File Structure

live-emotion-detector/
│
├── fer.h5 # Pre-trained emotion classification model
├── haarcascade_frontalface_default.xml # Haar cascade for face detection
├── emotion_detector.py # Main script
└── README.md # Project documentation

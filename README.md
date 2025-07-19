# 🎭 Live Emotion Detector using Deep Learning

A real-time facial emotion detection system using OpenCV and a pre-trained CNN model. This project uses your webcam to detect faces and classify facial expressions into one of seven emotions using deep learning.

## 🧠 Features

- Real-time webcam emotion detection
- Face detection using Haar Cascade Classifier
- Emotion classification using a trained CNN model (`fer.h5`)
- Supports 7 emotions:
    - 😠 Angry
    - 🤢 Disgust
    - 😨 Fear
    - 😀 Happy
    - 😐 Neutral
    - 😢 Sad
    - 😲 Surprise


## 🛠️ Tech Stack

- Python 3.x
- OpenCV
- Keras (TensorFlow backend)
- NumPy


## 📂 File Structure

```
live-emotion-detector/
├── fer.h5                      # Pre-trained emotion recognition model
├── haarcascade_frontalface_default.xml   # Haar cascade XML for face detection
├── emotion_detector.py         # Main Python script
└── README.md                   # Project documentation
```


## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/live-emotion-detector.git
cd live-emotion-detector
```


### 2. Install Dependencies

Make sure you have Python installed. Then install the required libraries using pip:

```bash
pip install opencv-python keras numpy
```


### 3. Add Required Files

Ensure these two files are in the same folder as your script:

- `fer.h5`: Pre-trained CNN model file for emotion classification. You can use one trained on the FER-2013 dataset.
- `haarcascade_frontalface_default.xml`: XML file for face detection (available in OpenCV's GitHub or from your local OpenCV installation).


### 4. Run the Application

Use the following command to launch the emotion detection app:

```bash
python main.py
```

Press `q` to quit the webcam window.

## 📸 Demo

Demo coming soon — add a screenshot or video showing live predictions here.

## 📄 License

This project is open source and available under the MIT License. You’re free to use, modify, and share it.

## 🙌 Credits

- FER-2013 Dataset
- OpenCV
- Keras
- TensorFlow


## 💡 Future Improvements

- Add GUI using Tkinter or PyQt
- Integrate sound or visual alerts based on emotion
- Train on custom datasets for higher accuracy
- Deploy as a web app using Flask or Streamlit

This version includes:

- Clear setup instructions with exact pip command
- Emojis for visual clarity (can be removed if you prefer minimal)
- No references to any external files other than the model and XML you already use
- All in one self-contained file ✅

Let me know if you'd like a plain-text version without emojis or a matching `requirements.txt`!


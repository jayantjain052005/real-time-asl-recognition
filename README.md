
# Real-Time American Sign Language Recognition

A computer vision project that detects and classifies American Sign Language (ASL) hand gestures in real time using a webcam.  
The system uses **Python, OpenCV, MediaPipe, and Machine Learning** to recognize hand signs and predict the corresponding ASL alphabet.

---

## Project Overview

Communication barriers often exist for people who rely on sign language.  
This project aims to build a **real-time ASL recognition system** that can detect hand gestures from a webcam and classify them into ASL alphabets.

The model processes video frames, detects hand landmarks, extracts features, and predicts the corresponding letter.

---

## Features

- Real-time webcam-based hand gesture detection
- Hand landmark tracking using MediaPipe
- Machine learning based gesture classification
- Fast and lightweight implementation
- Supports ASL alphabet recognition

---

## Technologies Used

- Python
- OpenCV
- MediaPipe
- Scikit-learn
- NumPy
- Matplotlib

---

## Project Structure

real-time-asl-recognition/
│
├── data/                # Dataset used for training
├── models/              # Saved trained models
├── src/
│   ├── collect_data.py
│   ├── train_model.py
│   └── predict_live.py
│
├── requirements.txt
├── README.md
└── main.py

---

## Installation

1. Clone the repository

git clone https://github.com/jayantjain052005/real-time-asl-recognition.git

2. Navigate to the project folder

cd real-time-asl-recognition

3. Install dependencies

pip install -r requirements.txt

---

## How It Works

1. Capture video from webcam
2. Detect hand landmarks using MediaPipe
3. Extract relevant features from hand landmarks
4. Train a machine learning model
5. Predict ASL alphabet in real time

---

## Example Workflow

Webcam → Hand Detection → Feature Extraction → ML Model → ASL Letter Prediction

---

## Future Improvements

- Support full ASL words and sentences
- Improve model accuracy using deep learning
- Add graphical user interface (GUI)
- Deploy as a web or mobile application

---

## Inspiration

This project was inspired by various computer vision and sign language recognition tutorials available online.  
The implementation has been adapted and modified to build a real-time ASL recognition system using Python, OpenCV, and MediaPipe.

---

## Credits

Dataset: ASL Alphabet Dataset (Kaggle)

Libraries used:
- OpenCV
- MediaPipe
- Scikit-learn
- NumPy

---

## Author

Jayant Jain  
B.Tech Computer Science (AI)

GitHub: https://github.com/jayantjain052005

<<<<<<< HEAD
---
title: ASL Sign Language Detector
emoji: 🤟
colorFrom: blue
colorTo: purple
sdk: docker
pinned: false
---

# ASL Real-Time Sign Language Detector

Real-time American Sign Language (ASL) detection using MediaPipe hand landmarks and a scikit-learn classifier.

## How to Use
1. Click **Start Camera** to enable your webcam
2. Show your hand sign to the camera
3. The detected letter appears instantly with confidence score
4. Use the **Sign Reference** panel on the right to see all signs
5. Letters are automatically added to history when held for 1.5 seconds

## Tech Stack
- **MediaPipe** — hand landmark extraction (21 keypoints)
- **scikit-learn** — Random Forest / MLP classifier
- **Flask** — web server
- **OpenCV** — image processing
=======
# 🤟 SignBridge – AI Sign Language Detection System

## 🚀 Live Demo

👉 https://huggingface.co/spaces/jayantjain052005/asl-detector

---

## 🎯 Problem

Communication barriers exist for people with hearing and speech impairments, especially in real-time interactions.

## 💡 Solution

SignBridge is an AI-powered real-time sign language detection system that converts hand gestures into readable text using computer vision.

## ⚙️ Features

* 🎥 Real-time gesture detection
* 🤖 Machine learning classification
* ✋ Hand tracking using MediaPipe
* 💬 Instant text output

## 🛠️ Tech Stack

* Python
* OpenCV
* MediaPipe
* Scikit-learn
* Hugging Face Spaces (Deployment)

## ▶️ Run Locally

```bash
pip install -r requirements.txt
python app.py
```

## 📸 Demo Preview

(Add screenshots here)

## 🚀 Future Scope

* Voice output (Text-to-Speech)
* Sentence prediction
* Mobile app version
>>>>>>> a3a0823a590c8286de4ff94dbddc09c8b848dd39

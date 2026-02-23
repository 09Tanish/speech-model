
# 🎤 End-to-End Speech Emotion Recognition Using BLSTMs with Self-Attention
<img width="1043" height="254" alt="image" src="https://github.com/user-attachments/assets/768120b4-42f2-49d7-8c93-b7e46d1e4e3d" />


## 📌 Project Architecture

This repository contains the source code for a **Speech Emotion Recognition (SER)** system built using **TensorFlow 1.15**.

The system includes modules for:

* Feature Extraction
* Deep Learning Classification
* GUI Interaction
* Real-Time Audio Recording
* Statistical Visualization

Developed as an **Undergraduate Thesis Project**, this system provides a strong foundation for future improvements in speech emotion analysis.

---

## 🚀 Key Features

✅ End-to-End Deep Learning Model for emotion recognition from speech

✅ Feature Extraction using:

* Two Convolutional Neural Network (CNN) layers
* Mel-Spectrogram inputs

✅ Classification using:

* Two Bidirectional LSTM (BLSTM) cells
* Self-Attention Mechanism to focus on emotionally relevant speech frames

✅ Graphical User Interface (GUI)

* Built with PyQt5
* Training & Inference Support
* Accuracy Visualization
* Confusion Matrix Display

✅ Live Audio Recording Support

✅ Pre-recorded Audio Classification

✅ Multi-Domain Training Strategy
Improves generalization across different datasets.

---

## 📂 Project Structure

```id="3h8s9d"
Speech-Emotion-Recognition-System
│
├── SER.py                   # Main GUI entry point for training & inference
├── model.py                 # Core deep learning classification model
│
├── feature_extractors/      # Feature extraction modules
│                           # (End-to-End method used)
│
├── graphics/                # GUI implementation (PyQt5)
├── recording/               # Audio recording module (PyAudio)
│
├── best_current_model/      # Pre-trained model files
├── requirements.txt         # Project dependencies
└── README.md                # Project documentation
```

---

## 🛠️ Technology Stack

| Component        | Technology      |
| ---------------- | --------------- |
| Deep Learning    | TensorFlow 1.15 |
| Audio Processing | Librosa         |
| GUI              | PyQt5           |
| Audio I/O        | PyAudio         |
| GUI Styling      | qdarkgraystyle  |
| Voice Detection  | webrtcvad       |

---

## ⚡ Getting Started

### 1️⃣ Create Virtual Environment

```bash id="a92ksd"
python -m venv venv
```

Activate Environment:

**Windows**

```bash id="k3mds9"
venv\Scripts\activate
```

**Linux / Mac**

```bash id="z8l29s"
source venv/bin/activate
```

---

### 2️⃣ Install Dependencies

```bash id="o7pl21"
pip install -r requirements.txt
```

---

### 3️⃣ Install TensorFlow 1.15

⚠️ Required since newer versions are not compatible

```bash id="v4s7ak"
pip install tensorflow==1.15
```

---

## ▶️ Running the Application

Launch the GUI for:

* Model Training
* Emotion Inference
* Real-Time Audio Recording
* Visualization

```bash id="n2s0lq"
python SER.py
```

---

## 📊 Model Capabilities

* Speech Emotion Recognition from Mel-Spectrogram Inputs
* Real-Time Voice Activity Detection
* Emotion Classification via BLSTM
* Self-Attention-based Temporal Feature Selection
* Accuracy & Confusion Matrix Visualization

---

## 📁 Pre-Trained Model

Best performing trained models are stored in:

```id="m5x91p"
best_current_model/
```

These can be directly used for inference without retraining.

---

## 📌 Notes

* Compatible with **TensorFlow 1.x only**
* Python version recommended: **Python 3.6 – 3.7**
* Ensure microphone permissions are enabled for live recording.

---

## 🤝 Contributing

1. Fork the repository
2. Create your branch

```bash id="7k19sd"
git checkout -b feature/NewFeature
```

3. Commit changes

```bash id="9p1sl0"
git commit -m "Added new feature"
```

4. Push to GitHub

```bash id="u2ls0q"
git push origin feature/NewFeature
```

5. Open a Pull Request

---

## 📝 License

This project is developed for academic research purposes.
Feel free to modify and extend for non-commercial use.

---


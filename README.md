# 🎯 Human Action Recognition System

> Real-time activity classification from video using deep learning — CNN + BiLSTM + MediaPipe Pose

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python) ![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow) ![MediaPipe](https://img.shields.io/badge/MediaPipe-Pose-green) ![SQLite](https://img.shields.io/badge/SQLite-DB-lightgrey?logo=sqlite)

---

## 🔍 Problem Statement
Surveillance and monitoring systems need to automatically classify human activities in real time without manual review. This project builds a deep learning pipeline to identify actions like walking, running, sitting, and waving from live or recorded video.

## 🏗️ Architecture
```
Video Input → MediaPipe Pose → 30-frame Landmark Sequences → CNN Feature Extraction → BiLSTM Temporal Modeling → Action Classification
```

## 📊 Results

| Model | Accuracy | Notes |
|---|---|---|
| CNN + BiLSTM | 91%+ | Best performance |
| LSTM-only baseline | 78% | Comparison model |

## 🛠️ Tech Stack
- **Deep Learning**: TensorFlow/Keras, CNN, BiLSTM
- **Pose Estimation**: MediaPipe Pose (33 body landmarks)
- **Data Management**: SQLite, Pandas
- **Analysis**: Action frequency distribution, behavioral trend charts

## 🚀 How to Run
```bash
git clone https://github.com/thenamealok/Human-Action-Recognition-CNN-BiLSTM
cd Human-Action-Recognition-CNN-BiLSTM
pip install -r requirements.txt
python main.py
```

## 📁 Project Structure
```
├── data/               # Training sequences
├── models/             # Saved model weights
├── notebooks/          # EDA and training notebooks
├── utils/              # MediaPipe extraction helpers
├── main.py             # Entry point
└── requirements.txt
```

## 🎓 Built as part of CDAC ACTS Bangalore PG-Diploma in Big Data Analytics (2025–26)

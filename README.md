# Human-Action-Recognition-CNN-BiLSTM

## Overview
This project implements a Human-Action-Recognition-System (HAR). 
The system classifies human activities using pre-extracted video features and a trained deep learning model.

## Project Structure
- **Human Action Recognition System.ipynb** – Main notebook for loading data, model, and prediction
- **har_video_dataset/**
  - X.npy – Feature vectors extracted from video frames
  - y.npy – Encoded class labels
  - class_names.npy – Human action class names
- **har_video_model.pth/** – Trained PyTorch model files

## Technologies Used
- Python
- Jupyter Notebook
- NumPy
- PyTorch
- Deep Learning
- Computer Vision (Human Action Recognition)

## Model
A trained deep learning model is used to classify human actions based on extracted video features.

## Dataset
The dataset consists of NumPy arrays generated from video data for efficient training and inference.

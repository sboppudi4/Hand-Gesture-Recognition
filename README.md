# Hand Gesture Recognition

Real-time hand gesture recognition built with MediaPipe and machine learning classifiers for keypoint and point-history based inference.

## Overview

This repository contains an end-to-end implementation for hand gesture recognition using webcam input. It includes:

- real-time inference pipeline (`app.py`)
- trained classifier artifacts (`.tflite`, `.hdf5`)
- label and dataset files (`.csv`)
- Jupyter notebooks for model development workflows

## Repository Layout

```
hand-gesture-recognition-mediapipe-main/
├── app.py
├── keypoint_classification.ipynb
├── keypoint_classification_EN.ipynb
├── point_history_classification.ipynb
├── model/
│   ├── keypoint_classifier/
│   └── point_history_classifier/
└── utils/
```

## Prerequisites

- Python 3.10 or later
- Webcam-enabled machine
- `pip` package manager

## Installation

From the repository root:

```bash
cd hand-gesture-recognition-mediapipe-main
pip install opencv-python mediapipe numpy tensorflow
```

## Run the Application

```bash
cd hand-gesture-recognition-mediapipe-main
python app.py
```

## Included Assets

- pre-trained model files for inference (`.tflite`, `.hdf5`)
- label definitions for gesture classes
- notebook-based workflows for keypoint and point-history classification


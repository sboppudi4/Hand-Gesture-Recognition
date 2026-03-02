# Hand Gesture Recognition

Real-time hand gesture recognition using MediaPipe and pre-trained keypoint/point-history classifiers.

## Project Structure

- `hand-gesture-recognition-mediapipe-main/app.py`: main application entry point.
- `hand-gesture-recognition-mediapipe-main/model/`: model code, labels, and trained artifacts (`.tflite`, `.hdf5`).
- `hand-gesture-recognition-mediapipe-main/utils/`: utility modules.
- `hand-gesture-recognition-mediapipe-main/*.ipynb`: training and experimentation notebooks.

## Requirements

- Python 3.10+ recommended
- Webcam access

Install dependencies (if not already installed in your environment):

```bash
pip install opencv-python mediapipe numpy tensorflow
```

## Run

From the repository root:

```bash
cd hand-gesture-recognition-mediapipe-main
python app.py
```

## Notes

- The repository includes trained model files under `model/`.
- Jupyter notebooks are provided for keypoint and point-history classifier workflows.
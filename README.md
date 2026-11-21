# Traffic Sign Recognition and Detection Using CNN and YOLO

## Project Overview

This project investigates traffic sign recognition and detection using deep learning techniques. Three approaches are evaluated: a Convolutional Neural Network (CNN), a YOLO26n object detector, and an integrated YOLO–CNN pipeline.

## Dataset

The project uses the German Traffic Sign Recognition Benchmark (GTSRB), which contains 43 traffic sign classes.

- Training images: 39,209 (before validation splitting)
- Test images: 12,630
- Total images: 51,839

## Models

- **CNN:** Classifies traffic sign images into 43 classes.
- **YOLO26n:** Detects and classifies traffic signs using bounding boxes.
- **YOLO–CNN:** Uses YOLO for localization followed by CNN classification.

## Final Results

| Model | Accuracy |
|---|---|
| CNN | 98.22% |
| YOLO | 96.65% |
| YOLO–CNN | 98.25% |

The YOLO detector achieved an mAP@50 of 94.47% on the prepared GTSRB test set.

## Limitations

The models were primarily evaluated on cropped traffic sign images. YOLO did not detect traffic signs in four external road-scene photographs. Further training and evaluation on full road-scene datasets are needed.

## Repository Contents

- Jupyter Notebook: Project implementation and experiments.
- Student 4 files: Dataset configuration and YOLO training results.
- Student 5 files: YOLO optimization and evaluation results.
- Student 6 files: Final model comparison and integrated pipeline results.

## Tools and Libraries

Python, Google Colab, TensorFlow/Keras, PyTorch, Ultralytics YOLO, OpenCV, NumPy, Pandas, and Scikit-learn.

# Brain Tumor Detection using Deep Learning

This project uses convolutional neural networks (CNNs) to detect brain tumors from MRI images. It includes a data augmentation pipeline to improve training robustness and performance.

## Project Structure

- `Augmentation.ipynb`: Contains data preprocessing and augmentation code.
- `Brain_tumour_detection.ipynb`: Contains model training, evaluation, and prediction logic.

## Features

- Data augmentation (rotation, zoom, horizontal flips, etc.)
- CNN-based classification model
- Accuracy and loss visualization
- Model evaluation using confusion matrix and performance metrics

## Requirements

- Python 3.x
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- scikit-learn

Install dependencies using:

```bash
pip install tensorflow opencv-python numpy matplotlib scikit-learn

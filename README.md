# PRODIGY_ML_04
# Hand Gesture Recognition using Deep Learning

This project focuses on developing a hand gesture recognition system using the [LeapGestRecog Dataset](https://www.kaggle.com/datasets/gti-upm/leapgestrecog). The system can accurately identify and classify different hand gestures from images, enabling intuitive human-computer interaction and gesture-based control systems.

## Dataset
- **Source:** [Kaggle - LeapGestRecog](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)
- **Content:** 10 different gesture classes, recorded from 10 users with both hands.
- **Total Samples:** ~200,000 grayscale images
- **Image Size:** 320x240 pixels

## Model Overview
- Preprocessing of images (resizing, normalization)
- Label encoding of gesture classes
- Train-test split
- Built a Convolutional Neural Network (CNN) model
- Used `TensorFlow` / `Keras` for deep learning implementation
- Model evaluation on accuracy and loss metrics

## Objectives
- Recognize static hand gestures in real time
- Enable touchless interaction for systems using cameras or depth sensors


## Tech Stack
- Python
- Jupyter Notebook
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `opencv-python`
  - `tensorflow` / `keras`
  - `scikit-learn`


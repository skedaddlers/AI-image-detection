---

# 🎨 CNN-Based AI Art Classifier

This project implements a convolutional neural network (CNN) model for classifying AI-generated artworks using TensorFlow and Keras. It is a part of a final project of my Knowledge Based Engineering class.
This will be deployed on a website to ease the use of upload image directly and get the classification results.

* **`FP_RSBP.ipynb`** – Main notebook used for building, training, and visualizing a CNN model on an AI-generated artwork dataset.
* **`tes_model.ipynb`** – A lightweight utility notebook used for single-image predictions and quick model testing using the saved `.h5` model.

## Model Overview

* CNN architecture using Keras with multiple convolution and pooling layers
* Trained on a dataset of AI-generated art sourced from Kaggle (`ravidussilva/real-ai-art`)
* Uses transfer learning principles and custom tuning for optimal classification accuracy

## Dependencies

* TensorFlow / Keras
* NumPy, Pandas
* Matplotlib, OpenCV
* KaggleHub for dataset downloading

## Notes

* Model weights are saved in `CNN_art_classifier.h5`
* Do not overwrite the model file without retraining

---

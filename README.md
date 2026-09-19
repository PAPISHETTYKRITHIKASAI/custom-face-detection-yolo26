# Custom Face Detection using YOLO26

## Overview

This project implements a custom face detection model using YOLO26 and the Ultralytics framework. The model was trained on a custom annotated dataset to detect faces in images.

## About YOLO26

YOLO26 is a deep learning–based object detection model designed for real-time vision tasks. It follows the YOLO (You Only Look Once) approach, where an input image is processed to identify objects and their locations.

In this project, YOLO26 was used to train a custom face detection model on an annotated dataset.

## Deep Learning Approach

YOLO26 is a deep learning–based object detection model that uses convolutional layers to extract visual features from images. During training, the model learns visual patterns that help it identify and localize faces in new images.

The Ultralytics framework was used to load, train, validate, and perform inference with the YOLO26 model.

## Technologies Used

- Python
- YOLO26
- Ultralytics
- Google Colab
- Jupyter Notebook

## Dataset

A custom dataset containing 353 annotated images was used for training and validation.

The dataset was organized into training and validation sets, with corresponding images and YOLO-format labels.

> The original dataset and personal images are not included in this repository for privacy reasons.

## Model Training

The YOLO26 model was trained using the following configuration:

- Epochs: 50
- Image Size: 640 × 640
- Batch Size: 16
- Early Stopping Patience: 10
- Optimizer: Adam

## Project Workflow

1. Prepared and organized the custom face dataset.
2. Split the dataset into training and validation sets.
3. Configured the dataset using a `data.yaml` file.
4. Loaded the YOLO26 model using Ultralytics.
5. Trained the model on the custom dataset.
6. Evaluated the trained model using the validation data.
7. Used the trained model for face detection.

## Repository Contents

- `YOLO26_Face_Detection.ipynb` — Jupyter Notebook containing the project implementation and model training workflow.

## Future Improvements

- Improve detection performance with a larger and more diverse dataset.
- Evaluate the model using additional performance metrics.
- Deploy the trained model as a real-time face detection application.

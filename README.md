# American Sign Language Recognition System

A real-time American Sign Language (ASL) alphabet recognition system developed using Computer Vision and Machine Learning techniques. The project captures hand gestures through a webcam, processes the input, and predicts the corresponding ASL alphabet in real time.

## Project Overview

The goal of this project is to assist communication by recognizing American Sign Language hand gestures and converting them into alphabet predictions. The system follows a complete machine learning workflow including data collection, dataset creation, model training, and real-time inference.

## Features

- Real-time ASL alphabet recognition
- Webcam-based gesture detection
- Dataset creation and preprocessing
- Machine learning model training
- Live prediction and classification
- End-to-end computer vision pipeline

## Technologies Used

- Python
- OpenCV
- NumPy
- Pickle
- Machine Learning

## Project Structure

```text
collect_imgs.py        # Collect training images
create_dataset.py      # Create and preprocess dataset
train_classifier.py    # Train machine learning model
inference_classifier.py # Real-time prediction
data.pickle            # Processed dataset
model.p                # Trained model

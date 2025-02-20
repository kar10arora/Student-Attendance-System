# Face Recognition Attendance System

# Overview

This project is a face recognition-based attendance system that detects and identifies students in a classroom, marks their attendance, and records the data in a CSV file along with timestamps. Additionally, the model is capable of detecting emotions. The system is designed to function within a specific time range (9:30 AM - 10:00 AM).

# Features

Face detection and recognition for student identification.

Automated attendance marking.

Emotion detection.

CSV storage of attendance records with timestamps.

Timing Constraint: The model will only work between 9:30 AM to 10:00 AM and will not function outside this window.

# Dataset

A custom dataset was created for training and validation.

Training Data: 100 images.

Testing Data: 100 images.

# Model Performance

Final model accuracy: 62.00%

# Usage

Run the model using the Jupyter Notebook provided:

jupyter notebook Face_Recognition.ipynb

# Future Improvements

Increase dataset size for better accuracy.

Implement hyperparameter tuning.

Enhance emotion detection accuracy with additional training data.

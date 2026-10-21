AI-Art-versus-Real-Art Classifier

Overview

This project explores image classification using machine learning to distinguish between AI-generated artwork and real artwork.

The model was trained using Google Teachable Machine, providing hands-on experience with image classification, model training, and exporting trained models for future integration into applications.

Project Objectives

- Explore practical applications of image classification.
- Train a machine learning model to distinguish between two artwork categories.
- Understand how trained models and their associated files are organized.
- Prepare the model for potential integration into a web application.

Model Files

The repository contains the following exported model files:

- `model.json` — Defines the model architecture.
- `metadata.json` — Contains model metadata, including information about the classification classes.
- `weights.bin` — Stores the trained model weights.

These files work together as parts of the exported model.

Tools and Technologies

- Google Teachable Machine
- Machine Learning
- Image Classification
- JSON model configuration and metadata

Current Status

The model has been trained, and its exported files have been uploaded to GitHub.

A standalone application for uploading images and viewing predictions is planned as a separate project.

Limitations

The model's predictions depend on its training data and the variety of images it has learned from. It may misclassify images that differ from its training examples.

Its performance should be evaluated using independent test images before making claims about its accuracy or reliability.

Future Improvements

- Evaluate the model using unseen images.
- Document the training dataset and class labels.
- Measure classification performance using appropriate evaluation metrics.
- Develop a separate application that integrates the trained model.

Author

Gideon Oginni

AI/ML and Robotics Engineer

---

*Built as part of my practical journey into artificial intelligence and machine learning.*

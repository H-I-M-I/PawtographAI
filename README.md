# U-Net for Pet Segmentation

This project demonstrates the use of a U-Net model for segmenting pet images from the Oxford-IIIT Pets dataset. The model performs pixel-wise classification to distinguish pets from the background.

## Why This Project?
Pet segmentation is used in veterinary applications, smart pet monitoring systems, and interactive AI-driven pet filters in photography apps.

## Dataset Details & Preprocessing
- Uses the Oxford-IIIT Pets dataset, which consists of images of 37 different pet breeds.
- Labels include pixel-wise annotations for pet foreground and background.
- Preprocessing includes resizing images, normalizing pixel values, and data augmentation (rotation, flipping, and brightness adjustments).

## Features
- Uses a U-Net model for semantic segmentation.
- Trains on the Oxford-IIIT Pets dataset.
- Implements data augmentation and loss optimization.

## Code Overview
- Loads and preprocesses the Oxford-IIIT Pets dataset.
- Constructs a U-Net architecture for segmentation.
- Trains the model on pet images.
- Evaluates segmentation performance with visualizations.

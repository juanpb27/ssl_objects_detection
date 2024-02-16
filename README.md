# Single-Shot Learning for 3D Feature Detection with Multi-Scale Data Augmentation

This repository contains the implementation of a novel single-shot learning methodology for 3D feature detection, as detailed in our paper. By leveraging a single training image, our approach utilizes multi-scale data augmentation through 3D transformations to achieve robust object detection across various scales and orientations.

## Overview

Our method addresses the challenges of deep learning's dependency on extensive datasets by employing a single-shot learning framework that enhances the accuracy and robustness of 3D feature detection. This is particularly suitable for hardware-limited environments where data acquisition and computational resources are constrained.

## Key Components

- `Data/`: Contains the data from the 3D reconstruction.
- `Model/`: Includes the trained model checkpoints and code for the convolutional neural network (CNN) used in our study.
- `notebooks/`: Jupyter notebooks demonstrating the usage and results of our method.
- `tests/`: Scripts for creating synthetic data or doing secondary experiments.

## Results

The repository features key results demonstrating the method's superiority over traditional 2D approaches. For an in-depth understanding of the results and methodologies, please take a look at our paper.

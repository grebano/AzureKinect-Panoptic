# AzureKinect-Panoptic

## Project Overview

This project integrates Azure Kinect DK camera with advanced panoptic segmentation models to provide real-time scene understanding. The system captures video streams from an Azure Kinect device and applies a deep learning model (Detectron2) to identify and segment objects and scenes in the video.

## Features

- **Azure Kinect Integration**: Configure and receive video streams from the Azure Kinect DK camera
- **Real-time Panoptic Segmentation**: Apply state-of-the-art panoptic segmentation using Detectron2
- **GPU Acceleration**: Optimize processing with GPU support for faster inference
- **Dual-view Visualization**: Display both original and segmented video streams side by side

## Technical Components

- **Hardware**: Azure Kinect DK camera
- **Deep Learning**: Detectron2 panoptic segmentation model
- **Processing**: GPU-accelerated inference with adjustable framerate
- **Visualization**: Real-time parallel display of original and processed video streams

## Use Cases

- Indoor scene understanding
- Robotics and navigation
- Augmented reality applications
- Human-computer interaction research

## Requirements

- Azure Kinect DK
- CUDA-compatible GPU
- Python with Jupyter Notebook support
- Required libraries: Azure Kinect SDK, PyTorch, Detectron2, OpenCV

## Getting Started

See the Jupyter notebook in this repository for a complete implementation walkthrough.

# yolov8objectdetection
# YOLOv8 Object Detection - README

This README provides an overview of the code and its execution process for using YOLOv8, a deep learning model for object detection.
#### link to googlecolab : https://colab.research.google.com/drive/1tDLko9G_BGeJiVDkimD38q7cvJM4Imp6?usp=drive_link
## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Setting up the Environment](#setting-up-the-environment)
  - [Installing Dependencies](#installing-dependencies)
- [Object Detection](#object-detection)
  - [Viewing Box Locations](#viewing-box-locations)
- [Fetching a Dataset from Roboflow](#fetching-a-dataset-from-roboflow)
- [Training a Custom Model](#training-a-custom-model)
  - [Validating the Model](#validating-the-model)
- [Testing the Model](#testing-the-model)
  - [Testing on Validation Mode](#testing-on-validation-mode)

## Introduction

This code demonstrates the process of setting up, training, and using a YOLOv8 object detection model. YOLOv8 is known for its real-time object detection capabilities and is commonly used in computer vision tasks.

## Getting Started

### Setting up the Environment

1. Set the `HOME` variable to the current working directory.

### Installing Dependencies

2. Install the `ultralytics` Python package (version 8.0.20) using the following command:
   ```markdown
   !pip install ultralytics==8.0.20

## object-detection
Detecting Objects in a Sample Image
Use YOLO to detect objects in a sample image from a URL. The detected objects will have bounding boxes drawn around them.
Interfacing with YOLOv8 Using Python
Load the YOLOv8 model with pre-trained weights.

Perform object detection on the same sample image using the loaded YOLOv8 model with a python interface instead of cmd.

## viewing-box-locations
Extract and display the coordinates and confidence scores of the detected boxes.
Training a Custom Model
## fetching-a-dataset-from-roboflow
Create a datasets directory in the HOME directory.

Install the roboflow Python package to work with Roboflow datasets.

Download a dataset from Roboflow using the provided API key, specifying the project and version to download.

## training-a-custom-model
Train the YOLOv8 model on the downloaded dataset. Training details, including loss values, will be displayed during training.
## validating-the-model
Validate the trained model on a validation dataset, displaying precision, recall, and mAP results.
Testing the Model
## testing-on-validation-mode
Test the trained model on a validation dataset and save the detection results.

Display prediction results for the tested images.


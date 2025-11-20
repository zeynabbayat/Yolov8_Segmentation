# Yolov8_Segmentation
YOLOv8 Instance Segmentation for debris detection on satellite images. Includes Google Colab notebook, training and evaluation workflow, scripts, and results.
YOLOv8 Instance Segmentation for Debris Detection
This repository contains a complete workflow for training and evaluating a YOLOv8 instance segmentation model on satellite imagery to detect and segment debris, with all code run and tested in Google Colab.

##Features
Custom dataset preparation and formatting for YOLOv8

Training instance segmentation models with flexible hyperparameters

Evaluation and visualization of metrics (mAP@0.5, mAP@0.5:0.95, precision, recall)

Output of segmentation masks and annotated images

Export of trained model weights and result files

##Getting Started
Prerequisites
Python 3.8+

Google Colab (recommended)

CUDA-enabled GPU (for efficient training)

Libraries: PyTorch, Ultralytics YOLOv8, OpenCV, Matplotlib (install as needed in notebook)

##Dataset Preparation
Images and annotation files (COCO-style JSON format or YOLO format)

Upload your dataset to Google Drive and update paths in the notebook

##Usage
Open the notebook (yolov8_segmentation.ipynb) in Google Colab.

Follow the sections to:

Mount Google Drive and set paths

Install/upgrade necessary packages

Prepare your dataset

Configure training settings

Train YOLOv8 for instance segmentation

Evaluate model and plot metrics

Run inference on test images

Export trained weights and results

##Training
Adjust hyperparameters, batch size, image size, and number of epochs directly in the notebook. Monitor training/validation curves for loss and accuracy.

##Evaluation & Inference
The notebook provides code to calculate mAP, precision, recall, and to visualize segmented outputs.

Save or export results and trained weights to Google Drive.

##Notes
All steps are designed for Google Colab, but can be adapted to local environments.

For large datasets, check Colab's storage and runtime limitations.

Use suggested notebook cells to troubleshoot or extend functionality.

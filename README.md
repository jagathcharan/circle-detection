# YOLO Circle Detection System

## Overview

This project implements a YOLO (You Only Look Once) object detection system designed to identify and locate circles in images. The system is built using the YOLOv8 model and is trained on a synthetic dataset containing circles of various sizes, colors, and backgrounds, as well as negative examples (images without circles). The dataset is split into training, validation, and testing sets, with the goal of evaluating the model's performance using accuracy, precision, recall, and Intersection over Union (IoU) metrics.

## Features

- Circle Detection: Identifies and locates circles in images under various conditions.
- Custom Dataset:Includes circles of different sizes, colors, and backgrounds.
- Negative Examples: Incorporates images without circles to improve detection accuracy.
- Metrics Evaluation: Evaluates model performance using key metrics.
- YOLOv8 Implementation: Utilizes the latest YOLO model for robust object detection.

## Project Structure
Mounting drive -->  synthetic Data creation --> spliting the data --> training --> accuracy graphs --> testing 
README.md

## Prepare Dataset:
The dataset is prepared by creating the background creation functions generate various types of synthetic backgrounds for data preparation, including solid colors, gradients, noise, and patterns like stripes. These diverse backgrounds are used to enhance the robustness of the model by providing varied visual contexts during training.
Running the code automatically creates the synthic dataset to the mounted drive

## Training the Model:
Open the Google Colab notebook and run the training section.
Adjust hyperparameters as needed.

## Validating the Model:
Use the provided code to validate the model's performance on the validation dataset.
Evaluate metrics like accuracy, precision, recall, and IoU.

## Testing:
Test the images attached to the file to skip the traing process i have give the image data set and model to verification

## Accuracy
Precision
Recall
IoU (Intersection over Union)
Visualization
Visualizations of detected circles are generated using matplotlib and seaborn to analyze the results.


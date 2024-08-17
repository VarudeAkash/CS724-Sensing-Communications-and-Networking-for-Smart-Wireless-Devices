# Intelligent Exercise Recognition and Counting Band with IMU Sensors

## Overview

This project involves the development of a wearable exercise recognition and counting band equipped with 9-axis IMU sensors and integrated with an Arduino Nano BLE Sense. The band is designed to capture motion signals from the right shoulder, process and analyze these signals, and classify exercises in real-time. The system also includes an anomaly detection mechanism to enhance robustness and accuracy.

## Features

- **Real-Time Exercise Classification**: Utilizes a Convolutional Neural Network (CNN) to classify exercises based on motion data.
- **Anomaly Detection**: Implements K-means clustering-based anomaly detection to identify and flag unusual or incorrect exercise patterns.
- **Fitness Tracking**: Accurately counts exercise repetitions and provides immediate feedback to the user.

## Components

- **Arduino Nano BLE Sense**: Microcontroller with Bluetooth Low Energy (BLE) capabilities.
- **9-Axis IMU Sensors**: Measures motion and orientation data.
- **Convolutional Neural Network (CNN)**: Used for real-time classification of exercises.
- **K-means Clustering**: For detecting anomalies in exercise patterns.

## Setup and Installation

1. **Hardware Assembly**:
   - Integrate the Arduino Nano BLE Sense with 9-axis IMU sensors.
   - Attach the assembled hardware to a wearable band for the right shoulder.

2. **Software Configuration**:
   - Upload the code to the Arduino Nano BLE Sense.
   - Ensure the CNN model is trained and deployed for exercise classification.
   - Implement the K-means clustering algorithm for anomaly detection.

3. **Live Demonstration**:
   - For a visual demonstration of the system in action, view the video [here](https://drive.google.com/file/d/1IW32caFU-zByPyRzhUgisTez_ZOtdWq0/view?usp=drivesdk).

## Usage

1. Wear the band on the right shoulder.
2. Start the application to begin capturing motion signals.
3. Exercise as usual; the system will classify your exercise and count repetitions.
4. Anomalies or incorrect patterns will be flagged and reported.

## Results

The system has been successfully demonstrated to track exercises and provide feedback in real-time, ensuring accurate performance assessment and enhancing workout efficiency.


## Acknowledgments

- Special thanks to Dr. Amitangshu Pal who provided guidance throughout the development of this project.

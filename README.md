# Accident Detection and Alert System

This project implements a real-time accident detection and alerting system using deep learning. It uses a Convolutional Neural Network (CNN) model to process video feeds for accident detection, with OpenCV for image and video processing. Twilio API is integrated to send emergency alerts with accident location, while an Arduino module with a GPS tracker provides real-time location updates and alarm notifications.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Architecture](#architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Alert System Integration](#alert-system-integration)

## Introduction

The project is designed to detect accidents from real-time video feeds and send alerts with accident location details. This system can be deployed in vehicles or traffic monitoring stations to enhance emergency response and improve road safety.

## Features

- **Accident Detection**: Utilizes a CNN model to detect accidents in real-time video feeds.
- **Image Processing**: OpenCV processes images and videos.
- **Alert System**: Twilio API sends SMS alerts with accident location.
- **Location Tracking**: Arduino with GPS tracker provides real-time location and alarm notifications.

## Architecture

The system consists of the following components:

1. **CNN Model**: Detects accidents from processed video frames.
2. **OpenCV**: Handles image and video processing.
3. **Twilio API**: Sends SMS alerts to emergency contacts.
4. **Arduino with GPS Tracker**: Provides real-time location tracking and notifications.

## Installation

1. **Clone or Download the Repository**: Download the `accident_detection.ipynb` file to your local system.
2. **How to run**: Run the cells one after another
3. **Save the model**: Save your trained model and later use the trained model
4. **Twilio Setup**: Sign up for a Twilio account, create an API key, and add your credentials in the notebook or environment variables.
5. **Arduino Setup**: Connect the GPS module to Arduino and upload the tracking code through the Arduino IDE. 

## Usage

1. **Open the Notebook**: Start Jupyter Notebook or Colab, and open `accident_detection.ipynb`.
2. **Run All Cells**: Execute each cell to initialize the accident detection model, process the video feed, and set up alert mechanisms.
3. **Receive Alerts**: When an accident is detected, the system sends an SMS with the location details.

## Model Training

To train the CNN model:

1. **Prepare Data**: Collect or download labeled video datasets with accident and non-accident scenes.
2. **Train Model**: The training script is embedded in the notebook, allowing you to train the model by following the steps provided.

## Alert System Integration

- **Twilio**: Sends SMS alerts with accident location details.
- **Arduino with GPS Tracker**: Updates location of detected accident and sends alerts if configured.


# balkonboemanmanual

Introduction 

The goal of this project is to explore pigeon detection for the Balkonboeman: a connected device intended to help residents respond to pigeons on their balcony remotely.
This manual documents the technical experiments carried out in October 2026, including the hardware setup, model training, errors and tested solutions.
The camera works with its existing person-detection model. The custom model detects pigeons in validation images in Google Colab, but has not yet been installed on the camera. Detection on my own balcony and the connection to notifications have not yet been tested.

Required hardware and software

Hardware: Arduino Uno, Grove Base Shield, Grove Vision AI Module V1, Grove cable, USB cable for the Uno, USB-C cable for the camera, and a laptop.
Software and services: Arduino IDE, Seeed_Arduino_GroveAI library, Chrome, Google Colab, Google Drive, and Roboflow.

Manual overview

Steps 1–5: connecting the hardware and testing the camera.
Steps 6–14: initial model training, errors, and solutions.
Steps 15–23: recovering files, retraining, and comparing results.
Steps 24–25: reviewing the final status and documenting remaining work.


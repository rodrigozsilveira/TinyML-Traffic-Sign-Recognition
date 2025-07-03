# Traffic Sign Detection with TinyML

This project presents a low-cost embedded system designed to **detect the presence of traffic signs in images** using TinyML techniques.

## Hardware

- Arduino Nano 33 BLE Sense  
- CMOS OV7675 Camera  

## Software

- Framework: **Edge Impulse** for model development
- **Arduino IDE** for real time inferencing

## Dataset

The model was trained on a **public dataset from Kaggle**, modified to include both images with and without signs, ensuring class balance and quality control.  
Main dataset: [Road Sign Detection – Kaggle](https://www.kaggle.com/datasets/andrewmvd/road-sign-detection)

## Results

While downscaling (96x96) improves speed and memory usage, it can reduce accuracy in complex scenes (e.g., multiple signs, poor lighting, angled views). Despite this, the model was effective for its primary goal.

> **Developed at UNIFEI – IESTI | 2025**

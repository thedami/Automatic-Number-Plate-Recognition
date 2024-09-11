# Automatic Number Plate Recognition

This Jupyter Notebook showcases an Automatic Number Plate Recognition (ANPR) system, implementing the following core components:

## Overview
The project focuses on detecting and recognizing license plates from images using a combination of computer vision and machine learning techniques. The system is designed to automatically identify and extract license plate regions from images and then apply Optical Character Recognition (OCR) to convert the detected license plates into readable text.

## Key Components

### 1. Object Detection for License Plates
The code utilizes a pre-trained object detection model, which is fine-tuned through transfer learning to accurately detect license plates. The model identifies the region of interest (ROI) within an image, specifically targeting license plates. 

### 2. Computer Vision with OpenCV (`cv2`)
OpenCV (`cv2` library) is incorporated to enhance the detection process, enabling the system to handle license plates from various sources such as static images, video streams, or live camera feeds. The use of OpenCV allows for robust preprocessing, image handling, and real-time detection capabilities.

### 3. Optical Character Recognition (OCR)
After detecting the license plates, the system applies Optical Character Recognition (OCR) using the EASY OCR library to extract the text from the detected plates. This step translates the image regions of the license plates into machine-readable text.

### 4. Results and Output
The system outputs both the detected license plate regions (ROIs) and the extracted text. The results include:

- **Detected License Plate Images:** The specific regions of the images where the license plates were detected.
- **Extracted Text:** The number plate information extracted from the images using OCR.

## Summary
This project demonstrates how a combination of object detection, computer vision (using OpenCV), and OCR can be effectively used to build an Automatic Number Plate Recognition system. By applying transfer learning and fine-tuning an existing model, the system efficiently detects and extracts license plate information from various sources. The results are saved as images and text, providing a complete solution for license plate recognition.
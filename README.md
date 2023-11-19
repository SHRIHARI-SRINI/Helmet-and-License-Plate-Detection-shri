# Helmet-and-License-Plate-Detection-shri

![Helmet and License Plate Detection]

This project is a real-time video analysis application that performs Helmet and License Plate Detection. The application uses YOLOv3 for object detection, a pre-trained helmet detection model, and Tesseract OCR for license plate recognition.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

- Object detection for persons and vehicles using YOLOv3.
- Helmet detection for persons using a pre-trained neural network model.
- License plate recognition for vehicles using Tesseract OCR.
- Real-time video processing and visualization.

## Demo



![Demo](output.avi)

## Prerequisites

Ensure you have the following installed:

- Python 3.x
- Required Python packages: cv2, imutils, numpy, tensorflow, pytesseract, moviepy, pillow

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/SHRIHARI-SRINI/helmet-license-plate-detection.git
2. Navigate to the project directory:
   ```bash  
   cd helmet-license-plate-detection
3. Install dependencies:
   ```bash  
   pip install -r requirments.txt

## usage

4. Run the application:
   ```bash  
   python elmet_license_plate_detection.py

   
Select a video file when prompted.

See the real-time analysis and results in the Tkinter GUI.

## Contributing
Contributions are welcome! Please follow the Contributing Guidelines.

## License
This project is licensed under the MIT License.

## Acknowledgments
YOLOv3: https://pjreddie.com/darknet/yolo/
Tesseract OCR: https://github.com/tesseract-ocr/tesseract
Include any additional acknowledgments, libraries, or references.

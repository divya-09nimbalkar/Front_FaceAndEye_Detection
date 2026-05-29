# Front_FaceAndEye_Detection

## Overview

Front_FaceAndEye_Detection is a Computer Vision project developed using Python and OpenCV. The application detects human faces and eyes in real-time using a webcam or image input. Haar Cascade classifiers are used for accurate detection and visualization.

---

## Features

* Real-time face detection
* Eye detection inside detected faces
* Webcam support
* Bounding box visualization
* Simple and lightweight implementation
* Built with OpenCV and Python

---

## Technologies Used

* Python
* OpenCV
* Haar Cascade Classifiers

---

## Project Structure

```bash
Front_FaceAndEye_Detection/
│
├── haarcascade_frontalface_default.xml
├── haarcascade_eye.xml
├── main.py
├── requirements.txt
└── README.md
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/Front_FaceAndEye_Detection.git
```

### Navigate to the Project Folder

```bash
cd Front_FaceAndEye_Detection
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Requirements

Add the following inside `requirements.txt`

```txt
opencv-python
```

---

## How to Run

```bash
python main.py
```

---

## Working Process

1. Capture video from webcam
2. Convert frame to grayscale
3. Detect faces using Haar Cascade
4. Detect eyes within detected face region
5. Draw bounding boxes around detected objects
6. Display output in real-time

---

## Output

* Green rectangle around detected faces
* Blue rectangles around detected eyes
* Live webcam detection window

---

## Future Improvements

* Deep Learning based detection
* Face recognition system
* Emotion detection
* Attendance system integration

---

## License

This project is open-source and available for educational purposes.

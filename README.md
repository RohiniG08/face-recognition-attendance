# Face Recognition Attendance System

A Python-based attendance system that uses face recognition to identify registered users and automatically record their attendance.

## Features

- Register new users using their name and ID.
- Capture face images using a webcam.
- Train a face recognition model using registered face images.
- Recognize registered users through the webcam.
- Automatically record attendance.
- Store attendance records in CSV files.
- Display attendance through a web interface.
- Uses OpenCV for face detection and recognition.

## Technologies Used

- Python
- Flask
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- Joblib
- HTML
- CSS
- Bootstrap

## Project Structure

```text
face-recognition-attendance/
│
├── app.py
├── README.md
├── requirements.txt
├── haarcascade_frontalface_default.xml
├── background.png
│
├── Attendance/
│   └── Attendance files (.csv)
│
├── static/
│   ├── faces/
│   └── face_recognition_model.pkl
│
└── templates/
    └── home.html

## Requirements

- Python 3.10 or above
- Webcam

Install the required Python libraries using:

```bash
pip install -r requirements.txt

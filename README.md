# AI-Based Face Recognition Attendance Management System

An AI-based automated attendance management system developed using Python, OpenCV, Face Recognition, and MySQL. The system captures a student's face through a webcam, identifies the registered student using facial recognition, and automatically records attendance with the student's name, date, and time in a SQL database.

## 📌 Project Overview

Manual attendance management can be time-consuming and prone to errors. This project automates the attendance process using computer vision and face recognition technology.

The system captures a live image from the webcam, detects the face, compares it with registered face encodings, identifies the student, and records the attendance automatically.

## 🚀 Key Features

- Real-time face detection using webcam
- Face recognition using facial encodings
- Automatic student identification
- Automated attendance marking
- Records student name, date, and time
- SQL database integration
- Prevents the need for manual attendance entry
- Simple and user-friendly Python-based implementation

## 🛠️ Technologies Used

### Programming Language
- Python

### Python Libraries
- OpenCV (`cv2`) – Webcam access, image capture, and computer vision
- Face Recognition – Face encoding and face matching
- Pandas – Data processing and attendance management
- NumPy – Numerical operations
- Datetime – Date and time recording
- OS – File and directory management

### Database
- MySQL / SQL

## ⚙️ System Workflow

1. Start the attendance system.
2. Access the webcam.
3. Capture the student's face.
4. Detect the face from the captured image.
5. Generate the facial encoding.
6. Compare the encoding with registered student faces.
7. Identify the student.
8. Store the student's name, date, and time in the SQL database.
9. Display confirmation that attendance has been marked.

## 📂 Project Structure

```text
Face-Recognition-Attendance/
│
├── main.py
├── known_faces/
│   ├── student1.jpg
│   ├── student2.jpg
│   └── ...
│
├── database/
│   └── attendance.sql
│
├── requirements.txt
└── README.md

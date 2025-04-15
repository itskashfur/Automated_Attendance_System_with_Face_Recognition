# Automated Attendance System Using Face Recognition and Eye Blink Detection

[![OpenCV](https://img.shields.io/badge/OpenCV-5.0-blue)]()
[![Python](https://img.shields.io/badge/Python-3.8%2B-green)]()
[![dlib](https://img.shields.io/badge/dlib-19.24-red)]()

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [System Architecture](#system-architecture)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Testing Results](#testing-results)
7. [Future Enhancements](#future-enhancements)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction
An automated attendance system that uses face recognition for identification and eye blink detection for liveness verification to prevent spoofing attacks.

Key Benefits:
- Contactless and fast attendance marking
- Prevents photo/video spoofing
- Automated record-keeping

## Features
- Real-time face detection using Haar Cascade/MTCNN
- Face recognition via dlib/face_recognition
- Liveness detection using Eye Aspect Ratio (EAR)
- Attendance logging in CSV/SQLite
- Optional GUI interface (Tkinter/PyQt)

## System Architecture
1. Camera Input
2. Face Detection
3. Face Recognition
4. Eye Blink Check
5. Mark Attendance
6. Save to Database

## Installation
1. Clone the repository:
git clone https://github.com/yourusername/automated-attendance-system.git
cd automated-attendance-system

2. Install dependencies:
pip install opencv-python numpy dlib face-recognition pandas

3. For GPU support (optional):
pip install dlib --install-option="--USE_AVX_INSTRUCTIONS" --install-option="--USE_SSE4_INSTRUCTIONS"


## Usage
1. Register a new face:
python register_face.py --name "John Doe"

2. Run attendance system:
python attendance_system.py


3. View attendance records:
python view_attendance.py










# Overview

This project allows you to control your system's volume using hand gestures. By calculating the distance between the top points of your thumb and index finger, you can increase or decrease the volume in real-time. It leverages **MediaPipe** for hand tracking and **PyCaw** for volume control.

# Features

- Real-time hand tracking with MediaPipe
- Gesture-based volume control
- Adjustable sensitivity for volume changes
- Cross-platform compatibility

# Requirements

To run this project, you'll need:

- Python 3.6 or higher
- Required libraries:
  - `mediapipe`
  - `opencv-python`
  - `pycaw`
  - `numpy`


## How It Works

- The application captures video from the webcam and uses MediaPipe's hand tracking to detect the positions of the thumb and index finger.
- The distance between the top points of the thumb and index finger is calculated to determine the volume adjustment.
- The PyCaw library is used to change the system volume based on the calculated distance.

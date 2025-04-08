# ✋ Hand Landmarks Tracking (MediaPipe + OpenCV)

# 📌 Description

This project implements a real-time computer vision system that tracks and identifies hand landmarks using MediaPipe and OpenCV. The system accurately detects 21 keypoints per hand—including fingertips, joints, and the wrist—and visually overlays the data for gesture analysis. It provides smooth, low-latency tracking ideal for applications like gesture recognition, virtual control systems, and human-computer interaction.

# 🛠️ Technologies Used
OpenCV – for video capture and drawing utilities

MediaPipe – for landmark detection using the Hand Landmarker model

NumPy – for mathematical operations and smoothing logic

# ⚙️ Approach
Utilized MediaPipe’s Hand Landmarker model to detect 21 hand keypoints in each frame.

Integrated OpenCV to display the landmarks in real-time with helpful labels and hand annotations.

Implemented custom logic to determine whether the hand is open or closed, and which fingers are extended.

Added a moving average filter (buffer size = 5) to smooth landmark positions and reduce jitter.

# ✅ Results
Achieved real-time performance with low latency and high accuracy in detecting hand and finger positions.

Successfully identified hand gestures and individual finger states with minimal errors.

Modular and clean code structure allows easy integration into other computer vision projects like virtual mouse control or sign language interpretation.

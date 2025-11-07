# Face-landmark-Detection
Description
This project demonstrates real-time face landmark detection using Python, OpenCV, and MediaPipe. The model identifies key facial points (landmarks) such as eyes, eyebrows, nose, lips, and facial contour, making it useful for various computer vision applications like emotion detection, head pose estimation, face filters, AR effects, and more.

Features

Real-time webcam-based face detection
Detects 468 facial landmarks with high accuracy
Uses MediaPipe Face Mesh for lightweight and fast inference
Visualizes landmarks directly on the video frames
Simple, easy-to-understand Python code

Technologies Used

Python
OpenCV (for video capture and drawing)
MediaPipe (for Face Mesh landmark detection)

How It Works

Video frames are captured from the webcam using OpenCV.
MediaPipe's Face Mesh model processes each frame to detect facial landmarks.
Landmarks are drawn on the face in real-time.
The processed frame is displayed back to the user.

Use Cases

Face filters (like Snapchat / Instagram)
Face alignment before training ML models
Eye-blink or lip-movement detection
Head pose estimation

AR/VR face tracking

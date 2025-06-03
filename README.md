# yolov8-hand-gesture-recognition
# Hand Gesture Recognition using YOLOv8
This project implements real-time hand gesture recognition using a custom-trained YOLOv8 model. The model is capable of detecting 5 distinct gestures from live webcam input:
- Open Palm
- Thumbs Up
- Two Fingers
- Four Fingers
- Fist
## Features
- Real-time gesture detection via webcam
- Trained on custom datasset annotated via Roboflow
- Uses YOLOv8 for high-speed, accurate inference
- Easily extendable to more gestures or downstream tasks
## How It Works
1. **Data Collection**: Images of hand gestures are collected and annotated using Roboflow.
2. **Model Training**: A YOLOv8 model is trained on the annotated dataset (in YOLO format).
3. **Inference**: The trained model is used to detect and classify gestures in real-time from the webcam.
4. **Visualization**: Bounding boxes and labels for recognized gestures are drawn live on video frames.
## Download Dataset
Download the custom dataset from Roboflow: https://app.roboflow.com/ds/VgY9Kpzk9p?key=P2DjWCsPPS

# Real-Time Traffic Sign Detection
This project performs real-time detection of Indian traffic signs using a webcam and a pre-trained object detection model.
# 📸 How it works
The script captures frames from your webcam, detects traffic signs in each frame using a model, and displays the detected signs with labels and confidence scores in real time.
# 🧠 Requirements
Python 3.8+

OpenCV

A trained YOLO object detection model (model_1) compatible with your code

Ultralytics YOLOv8 (if applicable)
# 🗂 Class Labels
This project uses a list of 70+ Indian traffic sign classes (from Stop and Speed Limit signs to No Parking and School Zone).
# 🚀 Running the Script
python traffic_sign_detection.py
Make sure to replace model_1 with your actual model loading code, for example:

python
python traffic_sign_detection.py
Make sure to replace model_1 with your actual model loading code, for example:

from ultralytics import YOLO
model_1 = YOLO('path_to_your_model.pt')
Press q to quit the webcam feed.
# 📁 Notes
The model must be trained to recognize the 70+ class names provided in the class_names list.

Ensure your webcam is connected and accessible.

For best results, use a well-lit environment.


# Real-time Object Detection using YOLOv3

This Python script demonstrates real-time object detection using YOLOv3 (You Only Look Once), a popular deep learning model for object detection. The code utilizes the OpenCV library for computer vision tasks.

## Prerequisites
- Install OpenCV in your Python environment.
- Download the YOLOv3 weights file ('yolov3.weights') and configuration file ('yolov3.cfg') from the official YOLO website.

## Usage
1. Clone this repository.
2. Download the YOLOv3 weights and configuration files and place them in the project directory.
3. Run the script using the command:
   ```bash
   python detector.ipynb
   ```
4. The script will open your computer's webcam and perform real-time object detection.

## Classes
The script is configured to detect objects from the COCO dataset, and the corresponding class names are defined in the 'coco.names' file. The classes include 'person', 'car', 'dog', and many others.

**Note:** The script may require adjustments based on your specific use case and environment.

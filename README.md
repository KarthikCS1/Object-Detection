Object Detection using YOLO
This repository contains a Python script for real-time object detection using the YOLO (You Only Look Once) algorithm implemented through the Ultralytics library. The script utilizes a pre-trained YOLOv5 model to detect objects in a video stream captured from a webcam.

Prerequisites
Python 3
OpenCV (cv2)
Ultralytics
cvzone
Installation
Clone this repository to your local machine.
Install the required Python packages:
arduino
Copy code
pip install opencv-python-headless
pip install torch torchvision torchaudio
pip install git+https://github.com/ultralytics/yolov5
pip install cvzone
Usage
Ensure your webcam is connected to your machine.
Navigate to the directory where the script is located.
Run the script using the following command:
Copy code
python object_detection.py
The webcam feed will open, and objects detected by the YOLO model will be outlined with their respective class names and confidence scores displayed.
Class Names
The model can detect the following classes of objects:

Person
Bicycle
Car
Motorbike
Aeroplane
Bus
Train
Truck
Boat
Traffic light
Fire hydrant
Stop sign
Parking meter
Bench
Bird
Cat
Dog
Horse
Sheep
Cow
Elephant
Bear
Zebra
Giraffe
Backpack
Umbrella
Handbag
Tie
Suitcase
Frisbee
Skis
Snowboard
Sports ball
Kite
Baseball bat
Baseball glove
Skateboard
Surfboard
Tennis racket
Bottle
Wine glass
Cup
Fork
Knife
Spoon
Bowl
Banana
Apple
Sandwich
Orange
Broccoli
Carrot
Hot dog
Pizza
Donut
Cake
Chair
Sofa
Potted plant
Bed
Dining table
Toilet
TV monitor
Laptop
Mouse
Remote
Keyboard
Cell phone
Microwave
Oven
Toaster
Sink
Refrigerator
Book
Clock
Vase
Scissors
Teddy bear
Hair drier
Toothbrush
Acknowledgments
This script utilizes the YOLO algorithm implementation provided by Ultralytics.
The cvzone library is used for drawing bounding boxes and text on the detected objects.

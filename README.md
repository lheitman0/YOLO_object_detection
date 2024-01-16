# YOLO Object Detection

## Introduction
This repo is an implementation of the YOLO (You Only Look Once) object detection system. The pre trained model I used was through Ultralytics and can be found on their GitHub.

In this notebook, I demonstrate the application of YOLO for detecting objects in images using PyTorch, along with supporting libraries like OpenCV, NumPy, and PIL.

The notebook is capable of processing static images, video files, and even real time footage from your webcam.



## Results
These results showcase the way the model renders results. The labels are from the COCO classes.

![Result 1](results/YOLO_traffic_render.png)
![Result 2](results/YOLO_zidane_render.png)

## Next Steps
This YOLOv5 model is trained on the COCO classes, a list of everyday items. My plan is to expand the models capability by fine tuning it to detect other things which would allow for more functional use cases and a wider range of possibilities. 
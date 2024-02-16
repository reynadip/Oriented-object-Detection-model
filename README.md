# Oriented-object-Detection-model
Object detection using Yolo V8

Objective: 
The goal of this task was to detect oriented objects in the given dataset and their classification ,oriented object detection is a critical component of computer vision and machine learning applications. 

Data exploration: 
The above dataset consisted of 10 images of various scenes with oriented objects.The give dataset was not labeled so the dataset was labeled using auto labeling environment(i.e using autodistill),this helped in minimizing the hassle of labeling one by one as it consumes time .

Model Selection:
A YOLO(you only look once) model was used to detect the objects .For oriented object detection the YOLO algorithm is widely used in most of the studies, we can also use faster R-CNN algorithm , but YOLO is the most convenient one.

Hyper-parameter used:
In YOLOv8, the default learning rate is set to 0.001.

learning_rate=0.001

In YOLOv8, the default batch size is set to 64.

batch=64

In YOLOv8, the default input size is 608x608.

width=608
height=608

We have only a single class in our model i.e car

classes=01

The non-maximum suppression (NMS) threshold is the threshold used to eliminate overlapping bounding boxes.
In YOLOv8, the default NMS threshold is set to 0.45.

nms_threshold=0.45

In YOLOv8, the default IOU threshold is set to 0.5.
iou_threshold=0.5

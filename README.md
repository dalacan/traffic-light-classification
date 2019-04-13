# Traffic Light Classification
## Overview
The purpose of this project is to explore the various object detection models for the 
purpose of traffic light classification. The goal of this project is to find a suitable model 
for the [capstone project](https://github.com/dalacan/Project-Capstone), which will be used 
to identify the traffic light color of the self driving car in a simulator and real world 
scenario.

As the capstone project will be implemented in two vastly different scenarios, the exploration and 
test will be done using two different datasets which are:
- Real world images taken from Udacity's self driving car
- Simulator images taken from Udacity's self driving simulator

Choosing from the available models from [Tensorflow detection model zoo](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md), 
we have elected to test the following models for their accuracy and inference speed::
- ssd_inception_v2_coco
- ssd_mobilenet_v2_coco
- faster_rcnn_inception_v2_coco
- faster_rcnn_resnet101_coco

As traffic light detection will be performed in real time, inference speed is a critical component.

## Exploration
To explore the accuracy and inference speed of these models the following notebooks were setup:
- [Real World Traffic Light classification](./Traffic-Light-Detection-Real-World.ipynb)
- [Simulator Traffic Light classification](./Traffic-Light-Detection-Simulator.ipynb)

## Results

---
layout: single
classes: wide
permalink: /projects/
title: "Projects"

---

## Kaggle Xray Detection(Work In Progress)

* Kaggle competition to detect 14 different chest x-ray anomalies

* Train EfficientDet network and evaluate using COCO evaluation.

* Deployed locally using Flask, but intending to extend functionality with databases, deployment with Heroku.

* In this way, I can learn about other aspects of ML besides model creation/training. Find [Github](https://github.com/dmatos2012/pytorch-flask-chest-anomaly-detection) code.

![Sample demo from repo](/assets/images/demo.png)

## PointRCNN detections with ROS
* Implementation of SoA object detection in the KITTI dataset with ROS. 

* Detections are visualized in LiDAR and camera space using RVIZ.

![](/assets/images/pointrcnn_dets.png) 



[Github](https://github.com/dmatos2012/pointrcnn_detector_ros)

## Plant Instance Segmentation

* Implemented instance segmentation network Mask-RCNN to count and segment plants on a private dataset.

* Evaluated model qualitatively and quantitatively using COCO evaluation.

* Training performed with Google Cloud Platform

## CityScapes Semantic Segmentation
* Implemented network on which multiple experiments were performed such as changing optimizers, using regularization and changing input images to network

* Google Cloud training on CityScapes dataset


 [Paper]({{ site.url }}/documents/Cityscapes_Semantic_Segmentation_group12.pdf)  

## Robust Semantic Segmentation

* Implemented network on which we used the Synthia Dataset to do robust semantic segmentation. On there, we tested whether different data augmentation techniques such as Gamma, flip, saturation among others improved the network's performance.

* Google Cloud training on Synthia dataset

![](/assets/images/4r_020.png) ![](/assets/images/4s_020.png) 

 [Paper]({{ site.url }}/documents/5AUA0_Final_Paper.pdf)  


## KITTI Data to ROS bag

 * Tool to convert raw data from the automotive KITTI dataset to a ROS bag, using the ROS PointCloudLibrary.

 [Github](https://github.com/dmatos2012/cpp_kitti_2_rosbag)




## Kaggle Speech Recognition

* Implemented network which consisted of correctly classifying 1-second audio files using CNN. 

* Audio files were converted to spectrogram to be used as input to the CNN.

* Submited result to the [Kaggle speech recognition challenge](https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/overview)

[Paper]({{ site.url }}/documents/5LSL0_Speech_recognition.pdf)  
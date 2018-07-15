# Training-balloon-tracking-based-on-YOLO-v3
This repository is about train one-class data via  transfer learning based on YOLO v3 

When I doing my research, I have to track a balloon that is binded on a drone. We all know that YOlO V3 is a state of the art model used to detect and track object. Here are some steps and tricks when training my own dataset.


## 1.Darknet
First, I complied the darknet accroding to this repository (https://github.com/AlexeyAB/darknet#how-to-train-to-detect-your-custom-objects) on my Ubuntu.
## 2.Preparing dataset
I downloaded the 2300 balloon images and marked the box according to [BBox Label Tool](https://github.com/puzzledqs/BBox-Label-Tool). 
![GitHub Logo](/Users/liyachao/Desktop/box_ori.png)
(Before training, I used the convert.py to convert the the )



# face detection and recognition/
 Detection and recognise faces in images and videos using ComputerVision, OpenCV and python

## Face detection

OpenCV has a face detector module which is based on Single-Shot_Detector (SSD) framework with a ResNet base network (other OpenCV SSDs may use MobilNet as the base network). 

In this part we will see how to apply face detection to single input images and videos/webcam using OpenCV SSD framework. 

## Face recognition

In first step, reusing the above code, will apply face detection to videos, video streams and webcams. After detection, we will generate 128-d facial embedding of identifed faces. More the images provided for a particular face, better the model would perform. For example, for person "Tom", if we have 10 images with different views/angles, then this step will generate facial embedding for each photo. 

In step2, we will check new face embeddings with stored one to identify faces. 

These 2 steps should be executed as different scripts. Step-1 of generating and storing 128-d facial embeding is one time process whereas step-2 of comparing new face's embedding would be more frequent. 





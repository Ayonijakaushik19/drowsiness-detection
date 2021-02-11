# Drowsiness Detection using OpenCV  

Detects eye movements and alerts when the object is drowsy


## Applications
This can be used by riders who tend to drive for a longer period of time that may lead to accidents


### Code Requirements
The example code is in Python ([version 2.7](https://www.python.org/download/releases/2.7/) or higher will work). 

### Dependencies

1) import cv2
2) import imutils
3) import dlib
4) import scipy


### Description

A computer vision system that can automatically detect driver drowsiness in a real-time video stream and then play an alarm if the driver appears to be drowsy.

### Algorithm

Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye:.

<img src="https://github.com/dhrubajyoti89/drowsiness-detection/blob/main/eye1.jpg">

### Condition

It checks 20 consecutive frames and if the Eye Aspect ratio is less than 0.25, Alert is generated.

#### Relationship

<img src="https://github.com/dhrubajyoti89/drowsiness-detection/blob/main/eye2.png">

#### Summing up

<img src="https://github.com/dhrubajyoti89/drowsiness-detection/blob/main/eye3.jpg">


For more information, [see](https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/)


<h3> Contributions are welcomed!</h3>
First create an issue if you want to add new feauture or want to improve existing code. After that create a Pull Request. 

<h3> Raise the PR to the TEST branch !</h3>

<div> </div>

Make a folder named after `Test` , if the code is platform specific then please create subfolder named to that Operating system within that language folder. For example `Test/Linux`. Add README.md in it telling about compilation, installing dependencies and some screenshots of the updates. 

Join the Slack channel for discussions 👋 : [JOIN NOW](https://join.slack.com/t/crosswocproject/shared_invite/zt-m8x1cuc3-CXizvRk2kuCEqPnwkVjwNw)

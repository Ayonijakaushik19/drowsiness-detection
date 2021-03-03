# Drowsiness Detection using OpenCV  

Detects eye movements and alerts when the object is drowsy

## Applications

This can be used by riders who tend to drive for a longer period of time that may lead to accidents

### Code Requirements

The example code already has a Virtual Python Environment (in **drowsiness_detection_venv** Folder). Activate the virtual environment before running the programme.

```javascript
$ cd drowsiness_detection_venv
```

#### For Mac & Linux

```javascript
$ source Scripts/activate
```

#### For Windows

```javascript
$ Scripts/activate
```

### Dependencies

1) import cv2 (comes under opencv-python library)
2) import imutils
3) import scipy
4) import dlib

> dlib library has some prerequisites such as Cmake and some C++ libraries. These prerequisites are essential otherwise the programme may throw **RUN TIME ERRORS**.
>
>**For Windows :** 
[Refer Here](https://medium.com/analytics-vidhya/how-to-install-dlib-library-for-python-in-windows-10-57348ba1117f)
>
>**For Mac and Linux :** [Refer Here](https://www.pyimagesearch.com/2017/03/27/how-to-install-dlib/)

### Run The Programme

After activating the virtual environment run :

```javascript
$ python Drowsiness_Detection.py
```

### Description

A computer vision system that can automatically detect driver drowsiness in a real-time video stream and then play an alarm if the driver appears to be drowsy.

### Algorithm

Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye:.

![GitHub Logo](/Images/1.jpg)

### Condition

It checks 20 consecutive frames and if the Eye Aspect ratio is less than 0.25, Alert is generated.

#### Relationship

![GitHub Logo](/Images/2.png)

#### Summing up

![GitHub Logo](/Images/3.jpg)

For more information, [Click Here](https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/)

### Contributions are welcomed !

First create an issue if you want to add new feauture or want to improve existing code. After that create a Pull Request.

### Raise the PR to the TEST branch !

Make a folder named after `Test` , if the code is platform specific then please create subfolder named to that Operating system within that language folder. For example `Test/Linux`. Add README.md in it telling about compilation, installing dependencies and some screenshots of the updates. 

Join the Slack channel for discussions 👋 : [JOIN NOW](https://join.slack.com/t/crosswocproject/shared_invite/zt-m8x1cuc3-CXizvRk2kuCEqPnwkVjwNw)

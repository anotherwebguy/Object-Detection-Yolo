# YOLO (You Only Look Once) Object Detection using OpenCV in Python.

<div align="center">

![Forks](https://img.shields.io/github/forks/anotherwebguy/Object-Detection-Yolo)
![Stars](https://img.shields.io/github/stars/anotherwebguy/Object-Detection-Yolo)
![Issues](https://img.shields.io/github/issues/anotherwebguy/Object-Detection-Yolo)
![Pull Requests](https://img.shields.io/github/issues-pr/anotherwebguy/Object-Detection-Yolo?) 

</div>

OpenCV dnn module supports running inference on pre-trained deep learning models from popular frameworks like YOLO, TensorFlow, etc.<br><br>
This project implements image Object detection, video Object detection and Real Time video Object detection through webcam using YOLO (You Only Look Once) algorithm.<br>
For this project pretrained YOLOv3 models was used. The YOLOv3 implementation is from [darknet](https://github.com/pjreddie/darknet).

----
## Tech stack

<img src="https://img.shields.io/badge/python-%230175C2.svg?&style=for-the-badge&logo=python&logoColor=white"/>

## Important Modules Needed
#### 1. opencv-python:
    Pre-built CPU-only OpenCV packages for Python.
#### 2. numpy:
    NumPy can be used as an efficient multi-dimensional container of generic data. Arbitrary data-types can be defined
#### 3. argparse:
    The argparse module makes it easy to write user friendly command line interfaces.

----
<br>
I've used YOLO v3 for coding purpose in this repository.<br>
<b>YOLO (You Only Look Once)</b> is a very powerful and a fast algorithm in object detection. A strong understanding of the algorithm is essential before we start to code.<br>

### Before getting started, Make sure you have numpy and opencv installed. If not install them using pip
     pip install numpy
     pip install opencv-python
     
----     


## Steps to get started
### 1. Clone the repository
    git clone https://github.com/anotherwebguy/Object-Detection-Yolo.git
### 2. Move to the directory
    cd Object-Detection-Yolo
### 3. Download the pretrained weights [yolov3.weights](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqazYyNXpuSk9SdjZTY3pfQWM1YzB2c2FMRm9DZ3xBQ3Jtc0ttSW1mTkxiY0c4U3NZR1hlYUJRRTJQZVUyWXNJemkzQTlIeThqMWNNUENkZkQ5X3o5YTdFRnNUYTRISzVjX3U2ZlgyVWF5c3AtekpoRkhnZy1VcjJ4QXRmNHNtNEpGNkNsQlg1VkwtU25ld0RzTXUxYw&q=https%3A%2F%2Fpjreddie.com%2Fmedia%2Ffiles%2Fyolov3.weights)
### 4. Place the [yolov3.weights](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqazYyNXpuSk9SdjZTY3pfQWM1YzB2c2FMRm9DZ3xBQ3Jtc0ttSW1mTkxiY0c4U3NZR1hlYUJRRTJQZVUyWXNJemkzQTlIeThqMWNNUENkZkQ5X3o5YTdFRnNUYTRISzVjX3U2ZlgyVWF5c3AtekpoRkhnZy1VcjJ4QXRmNHNtNEpGNkNsQlg1VkwtU25ld0RzTXUxYw&q=https%3A%2F%2Fpjreddie.com%2Fmedia%2Ffiles%2Fyolov3.weights) in the yolo-coco directory   
### 5. For Object Detection in images
    python main.py --image-path 'path/to/image/'
### 6. For Object Detection in vidoes
    python main.py --video-path 'path/to/video/'
### 7. For Real time Object Detection using webcam
    python main.py    



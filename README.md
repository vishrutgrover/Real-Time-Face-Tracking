# Real Time Face-Tracking (Mediapipe, BlazeFace, Haar Cascade, MTCNN)
The purpose of this is to create a stable system of real-time face detection inside a live video feed. Positioning of the face detection module of the system should be highly efficient in detecting and tracking faces, and to minimize the lag as much as possible for optimal functionality.

Documentation: https://docs.google.com/document/d/175gP1YPAicIntVyl-T3qb4dC_nS7JLezCFVm-b4ooQ4/edit?usp=sharing
<br>
Project Demo: https://youtu.be/ayyROZQzPm4
<br>

## Models Implemented
1) Mediapipe Holistic Detection for Single Face
2) BlazeFace Model for Multi Face Detection using Mediapipe (Single Shot Detector (SSD))
3) Haar Cascade Classifier using OpenCV
4) MTCNN

### Models currently working on
1) YuNet (Fast and lightweight, almost 1/5th time taken by Haar Cascade)
2) YOLOv3-face (Taken from the YOLOv3 architecture)
3) Face Recognition Module (Detection as well as labelling faces with a single example (one-shot learning))

## Set-Up
Paste these commands in the command prompt of your working directory to get started.
~~~
git clone https://github.com/vishrutgrover/Real-Time-Face-Tracking.git
cd Real-Time-Face-Tracking
python3 -m pip install -r requirements.txt
~~~

Get weights from the drive link https://drive.google.com/drive/folders/1ZJ5Nlr03BunyZwa8DeCTgKgrE-YLCi_j?usp=sharing and save them in the ```weights``` folder which is present in the cloned file directory.

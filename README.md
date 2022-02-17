# dataset-DroneDetection

Drone Detection Image Dataset, it's based of videos from https://github.com/DroneDetectionThesis/Drone-detection-dataset


with follow preprocessing via Roboflow https://blog.roboflow.com/getting-started-with-roboflow/ :

Auto-Orient: Applied

Resize: Stretch to 416x416


and augmenations:


Outputs per training example: 3

Flip: Horizontal, Vertical

Crop: 0% Minimum Zoom, 34% Maximum Zoom

Rotation: Between -30° and +30°


The dataset contains 2465 annotated images with various size, quality and background of drone images for balanced classes and splitted to Training, Validation and Testing sets (2157, 206 and 102 respectively).

The images saved in Yolov5 structure (/images as .jpg and  /labels as .txt)

Free to download, use and edit.


drone detection - v1 drone detection v1
==============================

This dataset was exported via roboflow.ai on February 8, 2022 at 10:24 PM GMT

It includes 2465 images.
Drone are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Randomly crop between 0 and 34 percent of the image
* Random rotation of between -30 and +30 degrees



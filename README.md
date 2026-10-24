# YOLO26 Object Detection

Learning project: object detection, segmentation, depth estimation
and video counting using Ultralytics YOLO26 and OpenCV in Google Colab.

## What is inside
- Object detection on images with confidence thresholds
- IoU and NMS (Non-Maximum Suppression) demo
- 2D cutout and 3D point cloud from a single image
- Data table and graphs of detected objects
- Counting people and vehicles from video

## How to run
1. Open the notebook in Google Colab
2. Run: `pip install ultralytics transformers`
3. Upload your own image or video when asked

## Notes
- Depth values are relative, not real distances in meters.
- Counting accuracy depends on video quality and camera angle.

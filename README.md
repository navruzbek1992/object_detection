Detect objects real time using YOLOv3

## Getting Started

This repo shows how to easily apply YOLOv3 to detect objects in videos.

### Installing

[YOLOv3](https://github.com/ayooshkathuria/pytorch-yolo-v3) is required. Users should download models config files, weights and class names also called coco names. 
They should be moved to "model"folder.

Also, OpenCV is required. 

```bash
pip install -r requirements.txt
```

## Deployment

Video should be saved in "video" folder.

```bash
python object_detection_yolov3.py
```

It displays the video and detected objects.

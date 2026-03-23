# Object Detection using Faster R-CNN

Real-time object detection on video using pretrained Faster R-CNN ResNet50 FPN.

## What it does
- Detects 80 COCO object classes in video frames
- Draws bounding boxes with class names and confidence scores
- Filters detections by confidence threshold (0.5)
- Saves annotated output video

## Tech
PyTorch, torchvision, OpenCV

## Run
```bash
pip install torch torchvision opencv-python
python Object_Detection.py your_video.mp4
```

## Note
Built and presented at GITAM University Computer Vision workshop (200+ attendees)

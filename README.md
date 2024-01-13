# YOLO Video Object Detection

## Introduction

Real-time object detection in videos using YOLO (You Only Look Once) model.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- YOLO weights and cfg files

## Setup

1. Clone repository
2. Download YOLO files (from [YOLO website](https://pjreddie.com/darknet/yolo/))
3. Install dependencies: `pip install -r requirements.txt`

## Usage

1. Place input video in `input` directory.
2. Run detection script:

   ```bash
   python object_detection.py --input_video input/your_video.mp4 --output_video output/output_video.mp4

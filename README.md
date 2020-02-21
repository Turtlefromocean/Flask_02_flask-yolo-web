<DSC EWHA Handlang- 수화번역 프로젝트>
==================================
# keras-yolo3

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)

## Updated

Forked from [keras-yolo3 by qqwweee](https://github.com/qqwweee/keras-yolo3)
1. Change PIL library to OpenCV to handle the real-time video stream from camera.
2. Use flask to setup a web based stream server, detects objects and resopnses to web browser.
3. Setup yolov3 pre-trained weights and then start server with `python3 server.py`

## Introduction

A Keras implementation of YOLOv3 (Tensorflow backend) inspired by [allanzelener/YAD2K](https://github.com/allanzelener/YAD2K).

---

## Quick Start

1. Download YOLOv3-tiny weights from [YOLO website](http://pjreddie.com/darknet/yolo/).
2. Convert the Darknet YOLO model to a Keras model.
3. Run YOLO detection.

```
wget https://pjreddie.com/media/files/yolov3-tiny.weights
python convert.py yolov3-tiny.cfg yolov3-tiny.weights model_data/yolo.h5
```

![](https://github.com/rememberlenny/recognize-familiar-faces/blob/master/docs/img/header.jpg?raw=true)

# Setup

## Hardware

1x Raspberry pi zero
1x Pi camera v2
1x Huawei e3372 usb modem
1x USB phone battery charger

## Setup

1. Configure modem with SIM card
2. Set up Raspberry pi with camera using Motion to run when active and stream endpoint
3. Set up OpenCV machine for analyzing video for faces

## Active process

1. Run camera and stream video to server that analyzes stream
2. Identified faces stored as images and embedded
3. Embedded faces added to DB
4. Faces tagged with "session"
5. If photo fits category, trigger alert

---

# Links

## Reference
- https://github.com/deepinsight/insightface
- https://github.com/tadasbaltrusaitis/openface
- https://github.com/davidsandberg/facenet

## Inspiration
- https://www.nytimes.com/2019/04/16/opinion/privacy-technology.html
- https://www.nytimes.com/2019/04/17/opinion/data-privacy.html
- https://www.nytimes.com/interactive/2019/04/16/opinion/facial-recognition-new-york-city.html

## Code
- https://www.pyimagesearch.com/2019/04/15/live-video-streaming-over-network-with-opencv-and-imagezmq/

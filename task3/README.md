<h1 align="left">
    Social Distancing Detector
</h1>

A social distancing detector built with OpenCV using YOLO(COCO model) object detector

<h2> About<span style='font-size:100px;'></span></h2>	
<p>
Social distancing is a method used to control the spread of contagious diseases. It implies that people physically distance themselves from one another, reducing close contact, and thereby reducing the spread of a contagious disease (such as the COVID-19 Disease).
</p>

## Features:
* Object detection using the YOLO COCO model to detect only people in a video stream.
* Computes the pairwise distances between all detected people.
* Based on the computed distances, we determine whether social distancing rule is being violated or not.


## Installation Guide:

1. Clone the repo

```bash
   $ git clone https://github.com/faryal6/Social_Distancing_Detector.git
   $ cd Social_Distancing_Detector
```

2. Install dependencies

```bash
   $ pip install -r requirements.txt
```

3. Run the Social-distancing-detector.ipynb file

* YOLO COCO weights\
The weight file exceeds the github limits but can be download from <a href="https://pjreddie.com/media/files/yolov3.weights">here</a>.\
Add the weight file to the yolo-coco folder.



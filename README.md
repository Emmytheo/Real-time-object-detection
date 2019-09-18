## Intro

This is an implementation of Object detection using a MobileNet Single Shot detection caffemodel in python3.+.
This is ideal for image processing projects involving low compute power and Non-gpu systems like the raspberry pi, an average laptop or other python based SoC dev boards.

I've uploaded the model and prototxt files so feel free to clone and start running right away.

## Dependencies

Python3, imutils, numpy, opencv 3+.

### Getting started

first clone this Repo.
Then use the command:
python real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel

##Breakdown
--prototxt: is the path to the prototxt file.

--model: is the path to the caffemodel, This was trained on 20 classes.

This network detects the following with relatively high accuracy and with an FPS of over 12fps:

"background",
"aeroplane",
"bicycle",
"bird",
"boat",
"bottle",
"bus",
"car",
"cat",
"chair",
"cow",
"diningtable",
"dog",
"horse",
"motorbike",
"person",
"pottedplant",
"sheep",
"sofa",
"train",
"tvmonitor"

## Credits

Credits for this code go to [https://github.com/apoorvavinod] and Adrian Rosenbrok - the creator of the imutils library.

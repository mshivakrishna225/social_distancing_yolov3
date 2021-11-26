# social_distancing_yolov3
REQUIREMENTS:
You will need the following to run this code:
#Python 3.5.2
#Opencv(CV2) 4.2.0
#numpy 1.14.5
#argparse

For human detection:
yolov3.weights, yolov3.cfg files (weights file in not present because of size issue. It can be downloaded from 
here : https://pjreddie.com/media/files/yolov3.weights)

FILE STRUCTURE:
main.py     : Detects and calculates distance between humans
utills.py   : Contain functions to calculate distance, scale, transformed points
plot.py     : Contain functions to draw bird eye view and frame
models      : Contain yolo weights and cfg.(IMPT NOTE: weights file in not present because of size issue. 
              It can be downloaded from here : https://pjreddie.com/media/files/yolov3.weights)
data        : Contain video sample
output      : Contain output frames
output_vid  : Contain output videos(Empty for now)

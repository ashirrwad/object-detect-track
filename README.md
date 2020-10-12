# Object Detection, Tracking and Counting
The aim of this repo is to make an Object Detection and Tracking application which helps us manage
large events.

The project is in its early stages.

Review - 1:
Added functionality to detect and track objects, and counting the ins and out via a reference axis.
  
## Instructions to run the project
 
1. Install the modules in the requirements.txt file
2. Launch the people_counter.py with python2 with valid arguments 
```
# To read from and input stream and write it onto a file:
python people_counter.py --prototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt --model mobilenet_ssd/MobileNetSSD_deploy.caffemodel --input {input video} --output {output stream}

# To read from webcam and write it onto file:
python people_counter.py --prototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt --model mobilenet_ssd/MobileNetSSD_deploy.caffemodel --output output/webcam_output.avi
```
Additional Arguments:
 
1.Minimum probability to filter weak detections obtained from the neural net
 
`-c, --confidence"`
 
2.No of frames to skip between detections, default value 30
 
`"-s", "--skip-frames" `
 

This is a college project.

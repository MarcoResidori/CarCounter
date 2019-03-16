# Car Counter Application

This application is a slightly modified version of the people-counter written by Adrian Rosebrock and available at https://www.pyimagesearch.com/2018/08/13/opencv-people-counter/

## Usage

### Input: video recording
python3 car_counter.py --prototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt --model mobilenet_ssd/MobileNetSSD_deploy.caffemodel --input videos/video01.mp4 --output output/video01_output.avi

### Input: web cam
python3 car_counter.py --prototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt --model mobilenet_ssd/MobileNetSSD_deploy.caffemodel --output output/webcam01_output.avi

### Output Examples
https://github.com/MarcoResidori/car-counter-opencv/blob/master/output/video01_output.avi
https://github.com/MarcoResidori/car-counter-opencv/blob/master/output/video02_output.avi


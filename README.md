camera-calibration-opencv2
==========================

Camera Calibration using OpenCV cpp interface and Zhengyou Zhang's algorithm.

### Brief Intro
The code comes from samples/cpp/tutorial_code/calib3d/camera_calibration/ and all related comments can be found at [Camera calibration With OpenCV](http://docs.opencv.org/doc/tutorials/calib3d/camera_calibration/camera_calibration.html).

### Files
*   camera_calibration.cpp   
The main routine.
*   in_VID5.xml   
The file for settings.
*   VID5.xml   
The file for specifying image list if using captured shots for calibration.
*   out_camera_data.xml   
The name for output log file specified in in_VID5.xml.
*   out_camera_data.yml   
Another name for output log file specified in in_VID5.xml.
*   calib_pattern.pdf   
The pattern for printing(typically in A4 or A3 size).

### Calibration 
*   1. Printing the pattern and stick in a planar
*   2. Modify in_VID5.xml to adjust settings, I use a webcam referenced by id "1" here
*   3. Hold the camera to view the whole pattern, press 'g' after seeing the feature corners
*   4. Press 'ESC' after calibration and see the results in output log file


# usb_cam
This repository is a usb camera package, based of V4L devices specifically.  
To execute this package follow the following commands  
1. In the source directory of your catkin workspace, glone the repository by using the following command

    git clone https://github.com/shashankvkt/usb_cam.git
  
2.build the package by the following command

    catkin_make

3.source your bash file by the following command

    source devel/setup.bash

4.For a monocular camera, use the following command to run the launch file

    roslaunch usb_cam usb_cam-test.launch

5.In case of stereo camera, use the following command

    roslaunch usb_cam stereo_cam-test.launch

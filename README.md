# ASUS-Xtion-Pro-Live

<!--more-->

## Installation
* Enter the following codes in your terminal
```bash
sudo apt-get install ros-indigo-openni-camera
sudo apt-get install ros-indigo-openni-launch
```

* Test your Asus Xtion Pro Live with ROS
```bash
roslaunch turtlebot_bringup minimal.launch
roslaunch openni_launch openni.launch
rosrun image_view image_view image:=/camera/rgb/image_raw
```

## Useful Links that you might need to work with Asus Xtion Pro Live
1. [PCL Tutorials](http://wiki.ros.org/pcl/Tutorials#pcl.2BAC8-Tutorials.2BAC8-hydro.CA-fd58b424fe3346661f3310747bf6b8e64049beb2_)
2. [PCL Overview](http://wiki.ros.org/pcl/Overview)
3. [OpenCV Installation in Linux](http://docs.opencv.org/3.1.0/d7/d9f/tutorial_linux_install.html#gsc.tab=0)
4. [Install OpenCV with extra modules](https://github.com/opencv/opencv_contrib)

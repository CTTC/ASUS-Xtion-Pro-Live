# ASUS-Xtion-Pro-Live

## Installation
* Enter the following codes in your terminal

```bash
sudo apt-get install ros-indigo-openni-camera
sudo apt-get install ros-indigo-openni-launch
```

* Remember to modify `GlobalDefaults.ini`
```bash
sudo gedit /etc/openni/GlobalDefaults.ini
```
then uncomment the line: `;UsbInterface=2` (just delete the `;` symbol)

* Test your Asus Xtion Pro Live with ROS
```bash
roslaunch openni_launch openni.launch
rosrun image_view image_view image:=/camera/rgb/image_raw
```


## Some websites that you might find useful
1. [PCL Tutorials](http://wiki.ros.org/pcl/Tutorials#pcl.2BAC8-Tutorials.2BAC8-hydro.CA-fd58b424fe3346661f3310747bf6b8e64049beb2_)
1. [PCL Overview](http://wiki.ros.org/pcl/Overview)
1. [PCL official website](http://pointclouds.org/)
1. [pcl_ros tutorials](http://wiki.ros.org/pcl_ros/Tutorials)
1. [OpenCV Installation in Linux](http://docs.opencv.org/3.1.0/d7/d9f/tutorial_linux_install.html#gsc.tab=0)
1. [Install OpenCV with extra modules](https://github.com/opencv/opencv_contrib)
1. [cv_bridge tutorials](http://wiki.ros.org/cv_bridge/Tutorials)
1. [openni_launch tutorials](http://wiki.ros.org/openni_launch/Tutorials)
1. [Which topics do I need](http://wiki.ros.org/openni_launch/Tutorials/BagRecordingPlayback)

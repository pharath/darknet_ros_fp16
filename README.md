# darknet-ros-fp16

more detailed information: [original repo](https://github.com/Ar-Ray-code/darknet_ros_fp16)

## Installation
```bash
$ sudo apt install ros-eloquent-desktop ros-eloquent-v4l2-camera
$ source /opt/ros/eloquent/setup.bash
$ mkdir -p ~/ros2_ws/src
$ cd ~/ros2_ws/src
$ git clone --recursive https://github.com/pharath/darknet_ros_fp16.git
$ darknet_ros_fp16/darknet_ros/rm_darknet_CMakeLists.sh
$ cd ~/ros2_ws
$ ./compile.sh --messages --release
```

# Easys_ros
Easys is an in-water robot. This repository contains hardware and software source(ROS2).
![IMG_9673](https://github.com/tamago117/Easys_ros/assets/38370926/150ee971-6230-4fc3-9c5f-c7301954f7d2)
![P8132769](https://github.com/tamago117/Easys_ros/assets/38370926/9c8923b8-014f-4e5c-a402-4565e1488479)

## hardware
https://drive.google.com/drive/folders/1nr-dIgoqMnhwZie1suLELQvrDiUapply?usp=sharing

## software
### environment
- raspberry pi4 (higher than 4Gb RAM)
- ubuntu 22.04
- ROS2 humble

### installation
```
cd (your workspace)/src
git clone https://github.com/tamago117/Easys_ros.git
colcon build
```

### usage

```
# robot terminal
ros2 launch Easys_ros Easys_control.launch
```
```
# remote PC terminal
ros2 launch Easys_ros remote_control.launch
```


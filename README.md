# AG95-ROS

## About
Contains drivers that handle the interface between DH Robotics' AG95 two finger gripper and ROS.

## Setting up permissions
```bash
sudo usermod -a -G dialout ${USER}
sudo usermod -a -G tty ${USER}
```

## Usage
To execute the driver to control AG95 gripper, execute
```bash
roslaunch dh_gripper_driver dh_gripper.launch
```
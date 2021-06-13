
## Installation Instructions

Some specific ROS packages might be required in order to complete the project -


``` bash
$ sudo apt-get install ros-melodic-navigation
$ sudo apt-get install ros-melodic-map-server
$ sudo apt-get install ros-melodic-move-base
$ rospack profile
$ sudo apt-get install ros-melodic-amcl
```

## Run the Project

After completing the project, you can launch it by running the following commands first -

```bash
$ cd ~/catkin_ws
$ catkin_make
$ source devel/setup.bash
```

And then run the following in *separate* terminals -

``` bash
$ roslaunch ros_bot ros_world.launch
$ roslaunch ros_bot amcl.launch
$ rosrun ros_bot navigation_goal
```

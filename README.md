# UAVs@B ROS Intro

Materials from the UAVs@Berkeley Introduction to ROS Workshop.

### Demo Instructions

(using ROS Development Studio or a local install of ROS Kinetic)

#### Create a new ROS package

`cd catkin_ws/src`

`catkin_create_pkg chatter std_msgs rospy roscpp`

#### Build the workspace

`cd ~/catkin_ws`

`catkin_make`

#### Create a talker node

`cd ~/catkin_ws/src/chatter/src`

(Write the talker.py file)

#### Create a listener node

(Write the listener.py file)

#### Build the workspace again

`cd ~/catkin_ws`

`catkin_make`

#### Run the nodes!

(In separate terminals)

```
roscore
rosrun chatter talker.py
rosrun chatter listner.py
```


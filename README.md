Eye Contact
===========

ROS node for sophia to make eye contact.

Prerequisites
-------------
###### cmt_tracker
> Face Tracking Node
> https://github.com/hansonrobotics/HEAD/tree/master/src/vision/cmt_tracker


Build
-----
```sh
catkin_make
```

Run
---
```sh
roslaunch eye_contact eye_contact.launch
```

ROS Nodes
---------
#### /eye_contact

###### Publications: 
 * /sophia/safe/head/command [ros_pololu/MotorCommand]
 
###### Subscriptions: 
 * /camera/face_locations [pi_face_tracker/Faces]
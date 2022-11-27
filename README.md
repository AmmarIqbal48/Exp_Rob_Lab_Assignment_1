# Exp_Rob_Lab_Assignment_1
***STATE MACHINE***

This is a ROS package that simulates the architecture of a robot building an ontology of the map environment and uses finite state machine to explore the environment in an organized manner.The environment is composed of locations that are connected in a certain way depending on the choice of the user. The goal is to build a Finite State Machine (FSM), with the use of SMACH, that allows the robot to choose the behaviour to adopt depending on the situation. The robot is also provided a battery, periodically checked, that needs to be recharged after some time of using.

The map Onltogy:

![Screenshot 2022-11-26 143630](https://user-images.githubusercontent.com/104999107/204136374-54bc68d0-9947-414a-9b4a-7e8d1da8a72f.png)

In the map there is:
1) 2 corridors (C1 & C2) Location which has atleast 2 doors.
2) Special Room (E) Location which has 2 doors. (This is the place where robot charges itself)
3) 4 Rooms (R1,R2,R3 & R4) Location which has 1 door.

# final_proj_ws

**Clone this git repository url: https://github.com/swetangdev/final_proj_ws.git**

## **1. Execute following command to make source available**
$ echo "source ~/final_project_ws/devel/setup.bash" >> ~/.bashrc
$ echo "export TURTLEBOT3_MODEL=waffle" >> ~/.bashrc
Now close all open terminals.


## **2. Execute following commands in one terminal: This will launch turtlebot3 in virtual world**
$ cd ~/final_project_ws
$ catkin_make
$ roslaunch my_simulation my_world.launch

## **3. Open another terminal and execute following command to move the robot following waypoints.**
$ cd ~/final_project_ws
$ rosrun my_simulation waypoint.py

## **Following is the video of how Turtblebot3 move in virtual world following waypoints as mentiooned in python script.**
### Simulation Video: https://www.youtube.com/watch?v=i4NYrUKKA2M&list=PL87blzoK6DNO_UtJ_1l68xwOwgAujdqUL&index=1&t=2s&ab_channel=SwetangSwetang

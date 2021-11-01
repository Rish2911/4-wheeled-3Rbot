Step 1:
Copy the simple_car_1 folder and simple_car onto your ~/catkin_ws/src path.

Step 2: 
On a terminal in catkin: catkin_make clean && catkin_make 
                                     Source ~/catkin_ws/devel/setup.bash
Step 3:
To launch the robot in gazebo 
On a terminal in catkin_ws/src: roslaunch simple_car_1 template_launch.launch 

To launch the robot in rviz to see the lidar. Make sure to attach the insert lazer/scan and link it to simple_car_1
roslaunch siimple_car_1 display.launch 
Note:Run roscore

Step 4:
To run the robot in teleop: rosrun simple_car_1 teleop_template.py.
Use the navigation keys to move the robot

Step 5:

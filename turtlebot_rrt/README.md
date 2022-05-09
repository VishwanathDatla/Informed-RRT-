
#Dependencies:
Numpy, Rospy, Matplotlib and Gazebo.


#Packages 
Turtlebot2 

#Instructions to run the package

cd ~/catkin_ws/src/turtlebot_rrt/scripts
chmod +x turtlebot_rrt.py
cd ../../../
catkin_make
source ./devel/setup.bash
roslaunch turtlebot_rrt demo.launch x:=4 y:=3 yaw:=0

This launches gazebo and an additional terminal with instructions to enter the coordinates of start point and goal. 
A path is the generated and displayed 

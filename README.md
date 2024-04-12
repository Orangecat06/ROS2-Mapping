# ROS2-Mapping

This project makes use of ROS2 to have an iCreate3 robot map out any enclosed space and do a dance at the center of the mapped area. 
The project uses various publishers and subscribers as well as the following topics: IrIntensityVector, Twist, and Odometry. 
Nested if statements are created to have the robot map out a room using data from the IR sensors. Twist is used to allow the robot to rotate and move linearly. Odometry is used to locate the robots orientation with respect to its global coordinates. 

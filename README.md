# Robotics-Manipulators

The goal of this course is to create a real working robot. We will develop and use this manipulator robot to test the code and the concepts that we will cover during the course. We will also use a simulator to simulate the robot in our PC. We will learn ROS 2 - Robot OS.
Digital Twin - we will start by developing a simulation of our robot to test the new functionalities we will be implementing before installing them on the actual robot.
Control - Controlling and moving the joints and the motors of our robot. Coordinate the movements of each motor and understand the mathematics of robotics.
Kinematics - More elaborate movements and ensuring the robot executes them in a simple manner by automatically coordinating the movements of all the joints.
Alexa - give commands through Alexa voice assistant to the robot.
Build - Build the real robot using Arduino.
Structure of robot - It is a manipulator robot with three degrees of freedom and is equipped with a gripper for object manipulation. (Degree of freedom - number of variables needed to determine the state of the machine). The position of the gripper in the world is detemined by the angle formed by the base joint, elbow joint and sholder joint. The gripper state is open/closed. The control of the actuators (converts energy into mechanical motion) is entrusted to an arduino. 
Articulated parallelogram - the gripper stays parallel to the base for all the movements of the robot.

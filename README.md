# Mini Task -2
# IDEATION
# 1.SNAKE ROBOT USING ARDUINO.

# Problem Statement:
  Building a snake robot to which camera is attached and going through the way where there is no obstacle.
  
# Components Used:
  •	Arduino,
  •	Servo motors,
  •	Sensors,
  •	PCB,
  •	Camera.
# Ideation:
  ## Understanding the robot’s mechanism:
 Identifying whether obstacle is present or not -> Sending to Arduino -> Signal to servo motors                              whether to rotate or not.
The outer design of snake robot can be made using 3D printing etc..
Which sensor can be used to detect obstacles, Ultrasonic or Infrared ??

 
|  Sensors               |  Feasibility          |  Advantages                                               | Disadvantages      |
|------------------------|-----------------------|-----------------------------------------------------------|--------------------|
|    Ultrasonic sensor   | Easy to implement     |  Large range,accurate in calculating distance of obstacle.|                    |                 
|    Infrared sensor     |  Yes, much better way |  Short range, better bandwidth.                           | Inability to use in sunlight due to interface  |


In this project, it is enough to find whether the obstacle is present or not in the way and we want the sensor with short range so that it can go near to obstacle and turn. So the IR sensor is preferred. But if the robot has to work in sunlight, then ultrasonic sensor can be used. And making some manipulations in designing, we can increase the degrees of freedom of robot for the better locomotion. And fixing many cameras allows us to visual the whole surroundings of the robot. This is very useful in rescue purposes.

The detailed explanation of project is here …,
https://www.ri.cmu.edu/pub_files/2014/6/d_rollinson_robotics_2014.pdf






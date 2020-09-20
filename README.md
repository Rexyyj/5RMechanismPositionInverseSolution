# 5RMechanismPositionInverseSolution

## Introduction
It is a course design for the course "MATLAB foundation and engineering application" in Tongji University in 2018. 

## Design Requiremnets
1. The 3-DOF hybrid manipulator is shown in the figure below, which includes a planar 2-DOF parallel manipulator and a 1-DOF serial manipulator. The established SimMechanics model is required to include the detailed structure of the robotic arm joints and end effector, as well as modules for observing the movement of the robotic arm, such as an oscilloscope.
![image](https://github.com/Rexyyj/5RMechanismPositionInverseSolution/raw/master/figure/fig1.png)
2. The plane 2-degree-of-freedom parallel manipulator is shown in the figure below. It belongs to a 5-bar mechanism and has 5 rotating pairs, of which the two rotating pairs connected to the frame are driving joints. Suppose the axis of each rotating pair is along the basic coordinate system z axis.
![image](https://github.com/Rexyyj/5RMechanismPositionInverseSolution/raw/master/figure/fig2.png)
3. The 1 degree of freedom serial manipulator can move in the vertical direction (along the z axis of the basic coordinate system), and is connected to the plane 2 degree of freedom parallel manipulator through a moving pair.
4. The structural parameters (including the length of the rod) of the robot arm are freely designed.
5. The basic coordinate system of the robot arm is located at the lower left corner of the robot arm in the figure above.
6. The position and posture of the robot arm at the initial moment can be freely designed.
7. After 5 seconds, the end effector of the robotic arm moves to the target position in a straight line: x = 0.4m, y = 0.5m, and z = 0.2m.
8. After 5 seconds, the robotic arm stays at the target position.
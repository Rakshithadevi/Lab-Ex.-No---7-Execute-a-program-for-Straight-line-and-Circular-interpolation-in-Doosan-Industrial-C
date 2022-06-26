# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.

Linear Interpolation








Circular Interpolation

### output:

![image](https://user-images.githubusercontent.com/94165326/175799983-19b08637-3cf7-442a-b87d-f8f83f0832f2.png)

![image](https://user-images.githubusercontent.com/94165326/175799987-63321b0a-ff50-4046-8654-0692a98c4c36.png)

![image](https://user-images.githubusercontent.com/94165326/175799989-8d222877-b290-4ca1-a929-6ac5ad710cf4.png)

![image](https://user-images.githubusercontent.com/94165326/175799997-0f82932e-3b75-485d-8d90-7d4159589b18.png)

![image](https://user-images.githubusercontent.com/94165326/175800002-70b264b1-5348-4689-b758-deca83e5a2fe.png)
## Linear Interpolation:
![image](https://user-images.githubusercontent.com/94165326/175800021-1cf34980-99e1-4ff8-a204-ff53f1cd8b88.png)
## Circular Interpolation:

![image](https://user-images.githubusercontent.com/94165326/175800032-671b2a26-b51c-4204-83c9-9db17ff8ef80.png)






### Results 


A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully..

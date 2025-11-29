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

### output

<img width="1052" height="680" alt="244032058-571a2336-048b-4f6c-8579-3352bd208fc5" src="https://github.com/user-attachments/assets/74d1eac1-4e97-4a9a-ad9d-dbb4ed7c4b38" />

<img width="1037" height="672" alt="244032091-bf5c6bd9-8820-4397-99e5-6e76c6dc843c" src="https://github.com/user-attachments/assets/d17349b9-fd50-4a15-87ef-9702932d269e" />

<img width="1052" height="675" alt="244032175-95a717dc-fa78-4dd7-8231-e6be4f2db306" src="https://github.com/user-attachments/assets/81927f84-30c4-4554-a1f4-9b037d481ddc" />

<img width="1086" height="796" alt="244032222-1f19cbdd-a7f4-409e-aad9-07b5cce4943d" src="https://github.com/user-attachments/assets/a43a5d4f-591a-421d-80c7-aa1fee073451" />

<img width="1050" height="682" alt="244032284-8c39d6e6-25bf-4bbb-82c7-bfa9de52c742" src="https://github.com/user-attachments/assets/2a7e0c12-eaa1-48cd-a2a5-f19878c2ebdc" />

Linear Interpolation

<img width="1056" height="743" alt="243977617-6f3593f8-390e-41fd-87fc-d1831156addb" src="https://github.com/user-attachments/assets/2cd3c7ea-0639-4dbf-b153-6cacc83c222b" />

Circular Interpolation

<img width="1053" height="747" alt="243977629-e0892148-0080-4bda-adc1-5e8d9bfe4b39" src="https://github.com/user-attachments/assets/0436d0a8-bb80-42c4-b1b5-e6941b750578" />

### Results 
Thus,program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio is executed.
 

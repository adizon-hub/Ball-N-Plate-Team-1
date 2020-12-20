# Ball-N-Plate-Team-1

# 1- INTRODUCTION

  For this project we used a controller to help balance a ball on a plate system that must be designed using Matlab, Simulink and Coppelia. The overall goal of this system is keep   a ball balanced at the center of the plate and must be able to react accordingly to the ball’s position to avoid the ball rolling off the plate. 

# 2- SYSTEM MODELING

In the Figure ( ) is the ball and plate system free body diagram that is being used. To find the nonlinear equation of motion Eq (1) was obtained by using the free body diagram. Also Eq (2) and Eq (3) were found using the geometry in the figure ( ). 

<img width="370" alt="model1" src="https://user-images.githubusercontent.com/76410573/102726544-76e2b100-42d4-11eb-9b7c-9d6543911034.png">
Figure 1. Ball and Plate System

<br>
<br>

<img width="470" alt="equations1" src="https://user-images.githubusercontent.com/76410573/102726924-36d0fd80-42d7-11eb-9852-108088fde928.png">
Table 1: Equations Used
<br>
<br>
Using the nonlinear equation of a motion shown in Eq (4) it was then linearized by doing sin(theta) = 0 , which can be written as shown in Eq (5). Next, the transfer function, Eq (7), for one motor was found by taking the Laplace transform of the linearized equation, Eq (6). This transfer function equation will also be used for the second motor as well.  

<img width="469" alt="equations2" src="https://user-images.githubusercontent.com/76410573/102726930-4f411800-42d7-11eb-8d5b-9b582b36e3e8.png">
Table 2: Equations Used Continue


# 3- CONTROLLER DESIGN & MODEL SIMULINK

# 4- CONTROLLER IMPLEMENTATION


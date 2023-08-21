# RPC-project-Robodk
Repository that contains some exercises done while learning the software and the 2 manufacturing tasks chosen.

# Description of the files inside the folders
## Normal exercises
*InspectTransmission*
  
  Simple exercise to understand the functioning of mechanisms and target on surface, for this example I ignored the collision problem.
  
*03E_-_Organize_shapes_-_Bonus*
  
  Simple exercise that orders and stacks the objects of the same color in their correct place.
  
*Conveyor_bottles_monitor_change*
  
  Case study to understand the conveyors and events (the original code was with the light, I changed it into the monitor with the message inside it).
  
*Drillingtask*

  Simple exercise to simulate a drilling task using the ur5.
  
*Drillingtask2*

  A bit more complex case of the previous exercise (sideanddrill is the main program of this exercise).
  
*Test_paint*

  Simple exercise to simulate a painting task while understanding the target on surface tool.


## Assignments

*Laser_cutting_with_ur5*

  Exercise representing the laser cutting manufacturing task, a further implementation could be the pick up of the object that needs to be cut (from the home position) from a stack
  and then to put away on the left.
  
*Car_deburring_with_ur5*

  Exercise representing the deburring of a plastic car, the objects are picked from the stack and then put away on a second stack after the task is complete.


## Others

It is worthy to mention that both the assignments are collision free, however (at least for my pc) having the collision detection on makes the simulation very laggy, therefore if it is needed to check the truth of this I recommend to run the single calls in the main program separately and run the complete simulation without having it on.

Every task was done with the ur5 robot.
